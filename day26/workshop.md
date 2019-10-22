# workshop 26

`views.py`

```python
def signup(request):
    if request.user.is_authenticated:
        return redirect('articles:index')
    if request.method == 'POST':
        form = UserCreationForm(request.POST)
        if form.is_valid():
            user = form.save()
            auth_login(request, user)
            next_page = request.GET.get('index')
            return redirect(next_page or 'articles:index')
    else:
        form = UserCreationForm()
    context = {'form':form}
    return render(request, 'accounts/form.html', context)
```



`signup.html`

```html
{% extends 'base.html' %}

{% block title %}Accounts:: 회원가입{% endblock title %}

{% block container %}
<h2>회원가입</h2>
<form method="POST">
{% csrf_token %}
{{ form.as_p }}
<button type="submit">회원가입</button>
</form>
{% endblock container %}
```


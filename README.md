<p align="center">
  <a href="https://github.com/chaliiwaui/djangogirls">
    <picture>
      <source height="150px" media="(prefers-color-scheme: dark)" srcset="./blog/templates/blog/logo/brand-main.svg">
      <img height="150px" alt="Django Girls" src="./blog/templates/blog/logo/brand-alt.svg">
    </picture>
  </a>
</p>

<h1 align="center">Django Girls Zanzibar - Blog</h1>

<p align="center">
  Jumuiya inayofundisha wanawake jinsi ya kutengeneza programu kwa Django.<br>
  <em>The Django Girls tutorial blog, built during the Django Girls Zanzibar workshop.</em>
</p>

<p align="center">
  <a href="#-maelezo">📇 Maelezo</a> •
  <a href="#-kuanza">🎬 Kuanza</a> •
  <a href="#-quick-start">🚀 Quick Start</a> •
  <a href="#-structure">🏗️ Structure</a> •
  <a href="#-kuchangia">🤝🏽 Kuchangia</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12%2B-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Django-6.1-092E20?logo=django&logoColor=white" alt="Django">
  <img src="https://img.shields.io/badge/SQLite-dev%20DB-003B57?logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Bootstrap-5-7952B3?logo=bootstrap&logoColor=white" alt="Bootstrap 5">
  <img src="https://img.shields.io/badge/Workshop-Zanzibar%20🇹🇿-orange" alt="Django Girls Zanzibar">
</p>

---

## 📇 Maelezo

Django Girls ni jumuiya inayojitolea kufundisha na kuhamasisha wanawake katika ulimwengu wa teknolojia. Wanajenga ujasiri kwa wanawake kujifunza na kushiriki katika maendeleo ya programu na tovuti kwa kutumia mfumo wa Django wa lugha ya Python. Kupitia warsha na vikao vya kujifunza, Django Girls inawapa wanawake zana na ujuzi wa kujenga tovuti na programu, na kuwasaidia kujitokeza katika sekta ya teknolojia.

Jumuiya hii ina lengo la kuvunja vizuizi vya kijinsia katika teknolojia na kuunda mazingira ya kujifunza yenye usawa. Django Girls inawezesha wanawake kushiriki katika ulimwengu wa programu na kuunda mabadiliko chanya katika sekta ya teknolojia kwa kutoa rasilimali na msaada wa kiufundi. Kupitia jitihada zao, Django Girls inaleta wanawake pamoja kuunda jamii ya kujifunza na kusaidiana, na kuonyesha kwamba kila mwanamke ana uwezo wa kufanikiwa katika teknolojia.

<p align="center">
  <picture alt="Credits to Jackson Makinda">
    <source media="(prefers-color-scheme: dark)" srcset="./blog/templates/blog/img/banner/dark.png">
    <img alt="Django Girls Banner" src="./blog/templates/blog/img/banner/light.png">
  </picture>
</p>

> **Imemalizika 🎉** Django Girls Zanzibar ilikuwa mafanikio 🚀
> Ilikuwa ni furaha kuwa sehemu ya uzoefu wako wa kwanza wa Django. Hadi tutakapokutana tena.
>
> Vibe, Mikate, na Chokoleti 🤗❤️

## ✨ Features

This is the blog application from the [Django Girls tutorial](https://tutorial.djangogirls.org/), with Django Girls branding:

- **Post list** (`/`) - published posts ordered by publish date
- **Post detail** (`/post/<pk>/`)
- **Create** (`/post/new/`) and **edit** (`/post/<pk>/edit/`) posts through a `PostForm` (`ModelForm`)
- `Post` model with author (`AUTH_USER_MODEL`), title, text, created and published dates and a `publish()` helper
- Django admin registration for posts
- Templates with a light/dark Django Girls logo, custom `blog.css` and Bootstrap 5 from jsDelivr

## 🎬 Kuanza

Kuanza safari yako na Django Girls, tafadhali rejea kwa [Maelekezo](https://tutorial.djangogirls.org/) ya kina.

## 🚀 Quick Start

```bash
git clone https://github.com/chaliiwaui/djangogirls.git
cd djangogirls
python3 -m venv myvenv && source myvenv/bin/activate   # Python 3.12 or newer
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser   # to write posts via /admin/
python manage.py runserver         # http://127.0.0.1:8000
```

Run the (starter) test suite with `python manage.py test`.

## 🏗️ Structure

```
djangogirls/
├── manage.py
├── requirements.txt
├── djangogirls/            # Project settings, urls, asgi/wsgi
│   └── settings.py
└── blog/                   # The blog app
    ├── models.py           # Post
    ├── views.py            # post_list, post_detail, post_new, post_edit
    ├── forms.py            # PostForm
    ├── urls.py
    ├── admin.py
    ├── migrations/
    ├── static/css/blog.css
    └── templates/blog/     # base, post_list, post_detail, post_edit + logo/img/favicon
```

## ⚙️ Configuration

The project uses the tutorial defaults: SQLite database, `DEBUG = True` and a development `SECRET_KEY` hard-coded in `djangogirls/settings.py`. Before deploying anywhere, move `SECRET_KEY` to an environment variable, set `DEBUG = False` and fill `ALLOWED_HOSTS`.

## 🤝🏽 Kuchangia

Ikiwa unataka kuchangia kwenye mradi wa Django Girls, jisikie huru kuchangia.

### Wachangiaji 👥

Django Girls inawezekana kwa kazi ngumu na ujitoleaji wa wanawake wa Django na mimi (kama kocha).

Asante kwa michango yako yenye thamani! 🧡

## 📄 License

No license has been chosen yet.

## 👤 Author

**Jackson Makinda** (coach) - [makindajackson.com](https://makindajackson.com)

- 📧 Email: me@makindajackson.com
- 💼 LinkedIn: [Jackson Makinda](https://linkedin.com/in/makindajack)
- 🎨 Dribbble: [@makindajack](https://dribbble.com/makindajack)
- 🐦 Twitter: [@makindajack](https://twitter.com/makindajack)

---

Built with ❤️ in Dar es Salaam, Tanzania 🇹🇿

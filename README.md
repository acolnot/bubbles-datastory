# Back to the Future of Bubbles - Data Story

## Set up 

### 1. Prerequisites

Make sure you have **Ruby** and **Bundler** installed on your laptop.

### 2. Clone the Repository

```
git clone git@github.com:acolnot/bubbles-datastory.git  
cd bubbles-datastory
```

### 3. Install Dependencies
```
bundle install
```

## Run the website locally
```
bundle exec jekyll server
```

Local Address:
```
http://127.0.0.1:4000/
```

## Project Structure

```
bubbles-datastory/
├── _layouts/
│   ├── default.html        # Provided layout
│   ├── full.html           # Provided layout
│   └── bttf.html           # Custom Back to the Future layout
├── _site/
├── .sass-cache/
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── img/
│   │   └── icon.png
│   └── js/
│       └── scale.fix.js
├── _config.yml             # Site configuration
├── .gitignore
├── Gemfile                 # Ruby dependencies
├── Gemfile.lock
├── README.md               
├── LICENSE
├── index.md                # Homepage
└── theory.md               # Bubbles mathematics
```
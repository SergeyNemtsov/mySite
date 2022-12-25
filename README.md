# mySite

1. [**Главная**](#главная)
2. [**Вторая вкладка**](#втораявкладка)



________________
### Главная
______________

```Java script
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>QA Testing</title>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>
   
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="manifest" href="/site.webmanifest">
   
   <style>
        .rounded-img {
            width: 40%;
            border-radius: 60%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0,2);
            padding: 0.2em;
            margin-bottom: 1em;
        }
        body {
        background: #c7b39b url(585ae486ee766\ \(2\).jpg); 
        }
        
    </style>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65"
      crossorigin="anonymous"
    />

  </head>

  <body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark p-0">
        <div class="container">
          <a class="navbar-brand p-0" href="https://vladislaveremeev.gitbook.io/qa_bible/" target="_blank">
            <img src="QA.png" alt="Иконка" width="40">
          </a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="/">Главня</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="places.html">ВК Школа седого тестировщика</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>


    <div class="container">
      <div class="row">
        <div class="col-lg-6">
          <div>
            <img class="rounded-img" src="NFrHKWGU3GY.jpg" alt="Аватарка" />
            >
            <div class="text-white">
                <h1 class="fw-light">Основы Автоматизации</h1>
                <p>
                  <i class="fw-light">*Для участия в Обучении необходимо выполнить регистрацию.</i>
                </p>
        

                        <p class="fw-light">
                          Автоматизированное тестирование, в отличие от ручного, упрощает
                          процесс выявления багов с помощью специальных программ, чем
                          сокращает затраты и время на цикл тестирования. Другими словами,
                          это позволяет получить готовый программный продукт без багов в
                          более короткие сроки, чем при ручном тестировании.
                        </p>
                      
            
                
                </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
        <div class="row">
            <div class="col-lg-2">
    <a href="https://sedtest-school.ru/" target="_blank" class="btn btn-primary">Перейти на сайт
      </a>
      </div>
      </div>
    </div>
    <div class="container text-center">  
        <div class="text-white">
        <h1 class="fw-light">Регистрация</h1></div>
      <form action="/my-handling-form-page" method="post">
        <div>
          <label for="name"></label>
          <input type="text" id="name" name="user_name" placeholder="Name" />
        </div>

        <div>
          <label for="name"></label>
          <input
            type="text"
            id="password"
            name="user_password"
            placeholder="Password"
          />
        </div>

        <div>
          <label for="mail"></label>
          <input
            type="email"
            id="mail"
            name="user_email"
            placeholder="E-mail"
          />
        </div>
        
        <button class="btn btn-secondary">Зарегистрироваться</button>
        <div class="container">
        <div class="row">
            <div class="col-lg-3">
    </div>
            </div>
        </div>
                    
        </div>
      </form>
    </div>
  </body>
</html>

```



____________
### Вторая вкладка
______________

```Java script
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sed-test-school</title>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
      crossorigin="anonymous"
    ></script>

    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png" />
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png" />
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png" />
    <link rel="manifest" href="/site.webmanifest" />

    <style>
      .card {
        border-radius: 1em;
      }
      .card:hover {
        background-color: rgba(180, 159, 255, 0.2);
      }
      .card img {
        border-radius: 50%;
        width: 60%;
        margin: auto;
      }

      body {
        background: #c7b39b url(M.jpg);
      }
    </style>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65"
      crossorigin="anonymous"
    />
  </head>

  <body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark p-0">
      <div class="container">
        <a
          class="navbar-brand p-0"
          href="https://vladislaveremeev.gitbook.io/qa_bible/"
          target="_blank"
        >
          <img src="QA.png" alt="Иконка" width="40" />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="index.html"
                >Главня</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="places.html"
                >ВК Школа седого тестировщика</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <div class="container my-2 text-center">
      <div class="row row-cols-1 row-cols-md-2 row-cols-lg-5 g-10">
        <div class="col">
          <div class="card">
            <img src="1.jpg" class="card-img-top" alt="ВК" />
            <div class="card-body">
              <h5 class="card-title">ВК главная</h5>
              <p class="card-text">Тут тебя ждет обучение на практике!</p>
              <a
                href="https://vk.com/zapiskisedogotestera"
                class="btn btn-primary"
                target="_blanc"
                >Перейти</a
              >
            </div>
          </div>
        </div>

        <div class="col">
          <div class="card">
            <img src="1.jpg" class="card-img-top" alt="ВК" />
            <div class="card-body">
              <h5 class="card-title">Обсуждения</h5>
              <p class="card-text">Реальные отзывы, живых людей!</p>
              <a
                href="https://vk.com/board172009645"
                class="btn btn-primary"
                target="_blanc"
                >Перейти</a
              >
            </div>
          </div>
        </div>

        <div class="col">
          <div class="card">
            <img src="1.jpg" class="card-img-top" alt="ВК" />
            <div class="card-body">
              <h5 class="card-title">Статьи</h5>
              <p class="card-text">Читай и познавай все о тестировании!</p>
              <a
                href="https://vk.com/@zapiskisedogotestera"
                class="btn btn-primary"
                target="_blanc"
                >Перейти</a
              >
            </div>
          </div>
        </div>

        <div class="col">
          <div class="card">
            <img src="1.jpg" class="card-img-top" alt="ВК" />
            <div class="card-body">
              <h5 class="card-title">Тренинги</h5>
              <p class="card-text">От начинающего до Senior, легко!</p>
              <a
                href="https://vk.com/uslugi-172009645"
                class="btn btn-primary"
                target="_blanc"
                >Перейти</a
              >
            </div>
          </div>
        </div>

        <div class="col">
          <div class="card">
            <img src="1.jpg" class="card-img-top" alt="ВК" />
            <div class="card-body">
              <h5 class="card-title">Чат</h5>
              <p class="card-text">Просто напиши мне, отвечу на вопросы!</p>
              <a
                href="https://vk.com/im?peers=c50_-214067820_c48_-217471446&sel=-172009645"
                class="btn btn-primary"
                target="_blanc"
                >Перейти</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>

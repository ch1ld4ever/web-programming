<script setup>
// Эта часть выполняется при первоначальной загрузке компонента
</script>

<style>
.avatar {
    border-radius: 50%;
    width: 100%;
    }

.avatar-post {
    margin-top: 1rem; /* отступ сверху */
    font-size: 1.4rem; /* увеличить размер шрифта */
    text-align: center; /* выровнять текст по центру*/
    }

.avatar-text {
    color: rgb(140, 140, 140); /* цвет текста - серый*/
    font-size: 1.1rem; /* увеличить размер шрифта */
    text-align: center; /* выровнять текст по центру*/
    }  
    
    a[href^="mailto:"] {
    margin-left: 110px;
    font-size: 16px;
    line-height: 32px;
    color: grey;
  }    

    p {
        text-align: center;
    }

.row   {
        margin: center;
    }

</style>


<template>
<html>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>О нас</title>
    <link rel="stylesheet" href="bootstrap/css/bootstrap.min.css">
    <!-- <script src="bootstrap/js/bootstrap.bundle.min.js"></script> -->
    <link rel="stylesheet" href="bootstrap-icons/bootstrap-icons.css">
    <link rel="stylesheet" href="styles.css">
</html>
<main class="container">
    <p>Добро пожаловать!<br>Меня зовут Хрустик, и я люблю корм</p>
    <!-- <img src="img/main.jpg" class="img-fluid"> -->
    <div class="row">
        <div class="col-md-4">
            <div class="card border-dark my-3">
                <div class="card-body">
                <div><img src="views/kot.jpg" width="100" height="250"></div>
                <div class="avatar-post"><i class="bi bi-person"></i>Генеральный директор</div>
                <div class="avatar-text">Просто директор</div>
                <a href="mailto:mail@htmlacademy.ru">Напишите мне</a>
                </div>
            </div>
        </div>
    </div>
</main>

</template>
<script>
// Здесь исходный код компонента
</script>

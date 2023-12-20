<!DOCTYPE html>
<html lang="en">

<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>home</title>

   <!-- font awesome cdn link  -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css">

   <!-- custom css file link  -->
   <link rel="stylesheet" href="css/style.css">

</head>

<body>
   <a href="http://127.0.0.1:8000/admin/login/?next=/admin/">Администрирование</a>

   <header class="header">

      <section class="flex">

         <a href="home.html" class="logo">Soft Skills Sculpt</a>

         <form action="search.html" method="post" class="search-form">
            <input type="text" name="search_box" required placeholder="поиск..." maxlength="100">
            <button type="submit" class="fas fa-search"></button>
         </form>

         <div class="icons">
            <div id="menu-btn" class="fas fa-bars"></div>
            <div id="search-btn" class="fas fa-search"></div>
            <div id="user-btn" class="fas fa-user"></div>
            <div id="toggle-btn" class="fas fa-sun"></div>
         </div>

         <div class="profile">
            <img src="images/pic-1.jpg" class="image" alt="">
            <h3 class="name">Леонардо ДиКаприо</h3>
            <p class="role">Студент</p>
            <a href="profile.html" class="btn">Профиль</a>
            <div class="flex-btn">
               <a href="login.html" class="option-btn">Войти</a>
               <a href="register.html" class="option-btn">Регистрация</a>
            </div>
         </div>

      </section>

   </header>

   <div class="side-bar">

      <div id="close-btn">
         <i class="fas fa-times"></i>
      </div>

      <div class="profile">
         <img src="images/pic-1.jpg" class="image" alt="">
         <h3 class="name">Леонардо ДиКаприо</h3>
         <p class="role">Студент</p>
         <a href="profile.html" class="btn">Профиль</a>
      </div>

      <nav class="navbar">
         <a href="home.html"><i class="fas fa-home"></i><span>Главная</span></a>
         <a href="about.html"><i class="fas fa-question"></i><span>О нас</span></a>
         <a href="courses.html"><i class="fas fa-graduation-cap"></i><span>Курсы</span></a>
         <a href="teachers.html"><i class="fas fa-chalkboard-user"></i><span>Менторы</span></a>
         <a href="contact.html"><i class="fas fa-headset"></i><span>Связаться с нами</span></a>
      </nav>

   </div>

   <section class="home-grid">

      <h1 class="heading"></h1>

      <div class="box-container">



         <div class="box">
            <h3 class="title">Курсы</h3>
            <div class="flex">
               <a href="#"><i class="fas fa-code"></i><span>Критическое мышление</span></a>
               <a href="#"><i class="fas fa-chart-simple"></i><span>Финансовая грамотность</span></a>
               <a href="#"><i class="fas fa-pen"></i><span>Творческое мышление</span></a>
               <a href="#"><i class="fas fa-chart-line"></i><span>Лидерство</span></a>
               <a href="#"><i class="fas fa-music"></i><span>Навыки коммуникации</span></a>
               <a href="#"><i class="fas fa-camera"></i><span>Искусство дебат</span></a>
               <a href="#"><i class="fas fa-cog"></i><span>Ораторское искусство</span></a>
            </div>
         </div>

         <div class="box">
            <h3 class="title">Популярные темы</h3>
            <div class="flex">
               <a href="#"><i class="fab fa-html5"></i><span>Как грамотно расходовать бюджет?</span></a>
               <a href="#"><i class="fab fa-css3"></i><span>Как находить выход из какой-либо ситуации?</span></a>
               <a href="#"><i class="fab fa-js"></i><span>Страх быть осужденным</span></a>
               <a href="#"><i class="fab fa-react"></i><span>Как воспроизводить хорошее впечатление</span></a>

            </div>
         </div>


      </div>

   </section>



   <section class="courses">

      <h1 class="heading">Курсы</h1>

      <div class="box-container">

         <div class="box">
            <div class="tutor">
               <img src="c:\Users\home\Desktop\ИТ СТАРТАП\ИТ-СТАРТАП 1\desgin\images\pic-2.jpg" alt="">
               <div class="info">
                  <h3>Некрасова Наталья</h3>
                  <span></span>
               </div>
            </div>
            <div class="thumb">
               <img src="https://i.pinimg.com/564x/2e/59/9e/2e599eae24fbce4296b1b7575f544d76.jpg" alt="">
               <span></span>
            </div>
            <h3 class="title">Критическое мышление</h3>
            <a href="playlist.html" class="inline-btn">Подробнее</a>
         </div>
         <div class="box">
            <div class="tutor">
               <img src="c:\Users\home\Desktop\ИТ СТАРТАП\ИТ-СТАРТАП 1\desgin\images\pic-7.jpg" alt="">
               <div class="info">
                  <h3>Айтматова Асель</h3>
                  <span></span>
               </div>
            </div>
            <div class="thumb">
               <img src="https://i.pinimg.com/564x/d1/55/72/d15572a315e55b586f63c2397645d60c.jpg" alt="">
               <span></span>
            </div>
            <h3 class="title">Лидерство</h3>
            <a href="playlist2.html" class="inline-btn">Подробнее</a>
         </div>
         <div class="box">
            <div class="tutor">
               <img src="c:\Users\home\Desktop\ИТ СТАРТАП\ИТ-СТАРТАП 1\desgin\images\pic-9.jpg" alt="">
               <div class="info">
                  <h3>Щербаков Константин</h3>
                  <span></span>
               </div>
            </div>
            <div class="thumb">
               <img
                  src="https://avatars.mds.yandex.net/i?id=b14ce8dd97c4393bcae5fd1eed64d016db6ed684-10102345-images-thumbs&n=13"
                  alt="">
               <span></span>
            </div>
            <h3 class="title">Финансовая грамотность</h3>
            <a href="playlist3.html" class="inline-btn">Подробнее</a>
         </div>




      </div>

      <div class="more-btn">
         <a href="courses.html" class="inline-option-btn">Все курсы</a>
      </div>

   </section>















   <footer class="footer">

      &copy; 2023 by <span>almau's students</span> | все права защищены!

   </footer>

   <!-- custom js file link  -->
   <script src="js/script.js"></script>


</body>

</html>

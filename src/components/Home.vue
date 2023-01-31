<template>
    <div>
        <loading :active.sync="isLoading"></loading>

        <head>
            <!-- Required meta tags -->
            <meta charset="utf-8">
            <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

            <!-- Bootstrap CSS -->
            <!-- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css"
                integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn"
                crossorigin="anonymous">
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css"> -->
            -->
        </head>

        <body>
            <!-- <div class="bg-secondary py-2 text-right" padding="50px">
                
                    <router-link to="/to_customer">
                        <a href="#" class="text-white" >商品頁面</a>
                    </router-link>
                    <router-link to="/admin/products">
                        <a href="#" class="text-white" >後台管理</a>
                    </router-link>

                
            </div> -->
            <div>
                <nav class="navbar navbar-dark fixed-top bg-secondary flex-md-nowrap p-0 shadow">
                    <a class="navbar-brand col-sm-3 col-md-2 mr-0" href="#">P â t i s s e r i e</a>
                    <form class="form-inline my-2 my-lg-0 text-white" id="nav">
                        <router-link to="/home">
                            <a class="nav-link text-white" href="#">首頁</a>
                        </router-link>
                        <router-link to="/to_customer">
                            <a class="nav-link text-white" href="#">商品頁面</a>
                        </router-link>
                        <router-link to="/admin/products">
                            <a href="#" class="nav-link text-white">後台管理</a>
                        </router-link>
                        <!-- <a class="nav-link text-white" href="#" @click.prevent="signout">登出</a> -->

                    </form>
                </nav>
            </div>


        </body>

        <header>
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                </ol>
                <div class="carousel-inner">
                    <div class="carousel-item active header-carousel-item bg-cover"
                        style="background-image: url(https://images.unsplash.com/photo-1602663491496-73f07481dbea?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NTd8fGNha2V8ZW58MHx8MHx8&auto=format&fit=crop&w=800&q=60);">
                    </div>
                    <div class="carousel-caption d-none d-md-block px-2 text-dark">
                        <h3>P â t i s s e r i e</h3>
                        <p>P â t i s s e r i ，來自法文甜點店的意思，就是如此簡單直白。</p>
                    </div>
                    <div class="carousel-item header-carousel-item bg-cover"
                        style="background-image: url(https://images.unsplash.com/photo-1586788680434-30d324b2d46f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NzV8fGNha2V8ZW58MHx8MHx8&auto=format&fit=crop&w=800&q=60);">
                    </div>
                    <div class="carousel-item header-carousel-item bg-cover"
                        style="background-image: url(https://images.unsplash.com/photo-1571050045617-cbbd5e68d181?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8OTJ8fGNha2V8ZW58MHx8MHx8&auto=format&fit=crop&w=800&q=60);">
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-target="#carouselExampleIndicators"
                    data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-target="#carouselExampleIndicators"
                    data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </button>
            </div>
        </header>

        <section class="bg-info text-white py-5">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-md-4">
                        <!-- <div class="mb-2"><i class="fa fa-users fa-5x" aria-hidden="true"></i></div> -->
                        <h3>嚴選食材</h3>
                        <p>產地直送或親自栽種，在其他地方吃不出的新鮮在此一次滿足。老闆每日天未亮就早起批貨，關照飼養的雞與牛，不外乎一些寒暄問暖以及觀察動物們的身體健康。這種小細節，就是保持新鮮的關鍵！
                        </p>
                    </div>
                    <div class="col-md-4">
                        <!-- <div class="mb-2"><i class="fa fa-users fa-5x" aria-hidden="true"></i></div> -->
                        <h3>職人工法</h3>
                        <p>餐飲科系出生，可以說是學院派的代言人。畢業後前往西方取經，千錘百鍊法式的製作工法，為的就是成就消費者每一口的幸福。
                        </p>
                    </div>
                    <div class="col-md-4">
                        <!-- <div class="mb-2"><i class="fa fa-users fa-5x" aria-hidden="true"></i></div> -->
                        <h3>客製化服務</h3>
                        <p>讓我們陪你度過人生每個值得紀念的重大時刻，有什麼想法歡迎私訊討論，只有沒想到的要求，沒有做不出來的甜點。
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <section class="container-fluid py-5 bg-light text-dark" style="position: relative;">
            <div class="row justify-content-end text-md-light">
                <div class="col-md-5 bg-cover"
                    style="
            position: absolute; top: 0; bottom: 0;
            background-image: url(https://images.unsplash.com/photo-1473256599800-b48c7c88cd7e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTEzfHxjYWtlfGVufDB8MHwwfHw%3D&auto=format&fit=crop&w=800&q=60);">
                </div>
            </div>
            <div class="container">
                <div class="col-md-7">
                    <h3>讓甜點療癒你的身心</h3>
                    <p>正當大家都告訴你甜食毒害眼睛毒害舌頭，我想告訴你的是，沒錯確實如此。</p>
                    <p>過多的放縱確實是毒，但是適當的放鬆是療癒。有太多正確又健康的規則限制著人們，但限制以外的才是人類內心的渴望，聆聽你的渴望，follow your heart。解開束縛才能重新被束縛。</p>
                    <p>你也可以不聽上述的建議無限放縱，讓老闆的店發大財，也是相當樂見。</p>


                    <router-link to="/to_customer">
                        <a href="#" class="btn btn-outline-info">查看更多</a>
                    </router-link>

                    <div class="row mt-3">
                        <div class="col-6">
                            <h4>甜點歷史</h4>
                            <p>歐洲是西點的主要發源地，人類歷史上最原始的甜點，是由麵粉調和油與蜂蜜而成的圓餅。在許多人類文明中，
                                甜點常被用來作為供俸神明的祭物，除講究材料品質外，形狀更為重要。貧窮的埃及人買不起鵝、牛等牲畜祭祀神明時，就製作動物形狀的蛋糕替代。後來，農村蛋糕逐漸演變成婚禮、生日等重要場合的食品。</p>
                        </div>
                        <div class="col-6">
                            <h4>21世紀甜點新風潮</h4>
                            <p>到了20世紀，法國的糕點業逐漸演化，更加專精在製作「甜點」上，類型也更加廣泛。過去十幾年間甜點越來越精緻、高價位，便開始出現了「高級訂製甜點」（pâtisserie haute couture）與「高級甜點」（haute pâtisserie）、「奢華甜點」（pâtisserie de luxe）等等說法，和融入巴黎人日常生活的「麵包甜點店」所賣的商品有所區隔。</p>
                        </div>
                    </div>
                </div>
            </div>


        </section>

        <!-- <section class="py-5">
            <div class="container">
                <h2 class="text-center my-3">如何那麼美味</h2>
                <div class="row">
                    <div class="col-md-6">
                        <div><i class="fa-brands fa-apple"></i></div>
                        <div>
                            <h3>美豔的時材</h3>
                            <p>工作，那麼你至少得吃一對兒鯨魚……我身邊的朋友們啊，沒有錢，但又找不到出路．如果多吃魚可以補腦讓人變聰明的話，珍惜生活上帝還讓你活著，年老的時候，然後選中一張百元大鈔。</p>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div></div>
                        <div>
                            <h3>美豔的時材</h3>
                            <p>工作，那麼你至少得吃一對兒鯨魚……我身邊的朋友們啊，沒有錢，但又找不到出路．如果多吃魚可以補腦讓人變聰明的話，珍惜生活上帝還讓你活著，年老的時候，然後選中一張百元大鈔。</p>
                        </div>
                    </div>
                </div>
                <div class="container">
                    <div class="row">
                        <div class="col-md-6">
                            <div><i class="fa-brands fa-apple"></i></div>
                            <div>
                                <h3>美豔的時材</h3>
                                <p>工作，那麼你至少得吃一對兒鯨魚……我身邊的朋友們啊，沒有錢，但又找不到出路．如果多吃魚可以補腦讓人變聰明的話，珍惜生活上帝還讓你活著，年老的時候，然後選中一張百元大鈔。
                                </p>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div><i class="fa-brands fa-apple"></i></div>
                            <div>
                                <h3>美豔的時材</h3>
                                <p>工作，那麼你至少得吃一對兒鯨魚……我身邊的朋友們啊，沒有錢，但又找不到出路．如果多吃魚可以補腦讓人變聰明的話，珍惜生活上帝還讓你活著，年老的時候，然後選中一張百元大鈔。
                                </p>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section> -->







        <!-- Modal -->
        <div class="modal fade" id="loginModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title" id="exampleModalLabel">登入</h5>
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">&times;</span>
                        </button>
                    </div>
                    <div class="modal-body">
                        ...
                    </div>
                    <div class="modal-footer">
                        <a href="#" class="mr-auto" data-dismiss="modal" data-toggle="modal"
                            data-target="#loginModal">切換到註冊</a>
                        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                        <button type="button" class="btn btn-primary">Save changes</button>
                    </div>
                </div>
            </div>
        </div>

        <!-- Modal -->
        <div class="modal fade" id="registerModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="modal-header bg-warning">
                        <h5 class="modal-title" id="exampleModalLabel">註冊</h5>
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">&times;</span>
                        </button>
                    </div>
                    <div class="modal-body">
                        ...
                    </div>
                    <div class="modal-footer">
                        <a href="#" class="mr-auto" data-dismiss="modal" data-toggle="modal"
                            data-target="#registerModal">切換到登入</a>
                        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                        <button type="button" class="btn btn-primary">Save changes</button>
                    </div>
                </div>
            </div>
        </div>


        <!-- Optional JavaScript; choose one of the two! -->

        <!-- Option 1: jQuery and Bootstrap Bundle (includes Popper) -->

        <!-- Option 2: Separate Popper and Bootstrap JS -->
        <!--
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.min.js" integrity="sha384-VHvPCCyXqtD5DqJeNxl2dtTyhF78xXNXdkwX1CZeRusQfRKp+tA7hAShOK/B/fQ2" crossorigin="anonymous"></script>
    -->


        <footer class="bg-light text-muted py-5">
            <div class="container">
                <ul class="list-inline text-center">
                    <li class="list-inline-item">© Copright 2017 六角血拼賣賣</li>
                    <li class="list-inline-item">
                        <a class="text-info" href="#">
                            <i class="fa fa-instagram" aria-hidden="true"></i> Instagrame</a>
                    </li>
                    <li class="list-inline-item">
                        <a class="text-info" href="#">
                            <i class="fa fa-facebook-square" aria-hidden="true"></i> Facebook</a>
                    </li>
                    <li class="list-inline-item">
                        <a class="text-info" href="#">About</a>
                    </li>
                </ul>
                <p class="text-center">Made with Bootstrap4</p>
            </div>
        </footer>
    </div>
</template>

<style>
.header-carousel-item {
    height: 450px;
}

.bg-cover {
    background-size: cover;
    background-position: center center;
}

.carousel-caption {
    background-color: rgba(255, 255, 255, 0.5);
}

@media (min-width: 768px) and (max-width: 991.98px) {
    .text-md-light {
        color: #fff;
    }
}
</style>

    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-fQybjgWLrvvRgtW6bFlB7jaZrFsaBXjsOMm/tB9LTS58ONXgqbR9W8oWht/amnpF" crossorigin="anonymous"></script>

<script>
                    // Example starter JavaScript for disabling form submissions if there are invalid fields
                    (function() {
                      'use strict';
                      window.addEventListener('load', function() {
                        // Fetch all the forms we want to apply custom Bootstrap validation styles to
                        var forms = document.getElementsByClassName('needs-validation');
                        // Loop over them and prevent submission
                        var validation = Array.prototype.filter.call(forms, function(form) {
                          form.addEventListener('submit', function(event) {
                            if (form.checkValidity() === false) {
                              event.preventDefault();
                              event.stopPropagation();
                            }
                            form.classList.add('was-validated');
                          }, false);
                        });
                      }, false);
                    })();
                    </script>


# moudle3_solution
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Mockup</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    <style>
        /* Custom styles */
        .navbar.scrolled {
            transform: translateY(-100%);
        }
        .dropdown-menu-wide {
            width: 100vw;
            background-color: #f8f9fa; /* Change to your desired color */
        }
        .page-heading {
            text-align: center;
        }
        .tall-section {
            height: 1000px;
            background-color: #f0f0f0; /* Change to your desired color */
        }
    </style>
        <link rel="stylesheet" href="/css/style.css">
    <script>
        $(window).scroll(function() {
            var scroll = $(window).scrollTop();
            if (scroll > 0) {
                $(".navbar").addClass("scrolled");
            } else {
                $(".navbar").removeClass("scrolled");
            }
        });
    </script>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-default" style="border-bottom: black 3px solid; border-top: black 3px solid; background-color: gray;">
        <div class="container">
            <div class="navbar-header" >
                <button type="button"  class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-collapse">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand" id="foodNavbar" style="color: black;" href="#" >Food, LLC</a>
            </div>
            <div class="collapse navbar-collapse" id="navbar-collapse" >
                <ul class="nav navbar-nav navbar-right">
                    <li class="visible-xs"><a href="#" style="color: black;">Chicken</a></li>
                    <li class="visible-xs"><a href="#" style="color: black;">Beef</a></li>
                    <li class="visible-xs"><a href="#" style="color: black;">Sushi</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Page Heading -->
    <div class="page-heading">
        <h1>Our Menu</h1>
    </div>

    <!-- Tall Section -->
    <div class="container" style="width: 100%;">
        <div class="row">
            <div class="col-xs-12 tall-section">
                <div class="chickenPart partMenu">
                    <p class="textHeader">Chicken</p>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas non quod sunt nesciunt accusamus alias, mollitia aliquid. Neque atque sequi rerum quod, minus temporibus! Ullam perspiciatis tenetur neque aspernatur odit mollitia unde nam animi facere commodi, impedit quasi cupiditate deleniti pariatur veniam eum saepe totam sunt magnam provident iste soluta fugit aliquid rem! Est, consectetur sit quis doloremque enim incidunt tempore dolore ex? Ex iste repudiandae unde beatae. Et amet culpa facere dignissimos consectetur quisquam, nisi tenetur consequatur non provident natus eveniet inventore, quibusdam iure? Reiciendis voluptas asperiores repudiandae quas eligendi excepturi autem est optio corrupti? Est exercitationem, deleniti perspiciatis, excepturi enim neque earum, quas asperiores at reiciendis vitae! Illo laboriosam quos officia architecto necessitatibus iusto dolore repellendus voluptatem, ipsam facere ab facilis ea maxime unde distinctio sit corporis voluptatibus commodi repudiandae? Voluptates quae non omnis. Ab non ipsa dicta autem, in ratione nihil mollitia nisi a placeat odio quisquam soluta, iste eum fuga itaque distinctio tempore! Quo eius cumque molestias accusamus omnis vitae exercitationem fuga in debitis mollitia corporis, quia sit porro fugiat cum, aperiam provident rem ut illo sapiente, aspernatur quae! Libero, dolore? Vero consectetur natus a aspernatur voluptas ex eligendi similique impedit at, nemo excepturi tempora dolorum saepe quisquam! Sequi officiis odio ad natus, quaerat laboriosam, ab eligendi consequuntur aut deserunt veritatis sit animi suscipit. Consequatur quasi ullam nemo! Labore optio assumenda tempore impedit accusamus. Molestiae dicta maiores voluptate eveniet, dolorem, officia quia earum quod quas saepe sint perferendis fugiat nesciunt ipsam fugit dolore tempora! Dicta facilis nam natus, perferendis sit illum delectus nemo odit id totam ea ipsam est ducimus accusantium ex officia hic? Dolores, iure harum alias accusantium explicabo dolore cupiditate temporibus maiores dicta sint! Nihil quae eos, quod ab cumque natus autem sit impedit voluptatem non tempore quidem accusamus voluptas unde sint quo ex repellendus quia, laboriosam architecto velit placeat nisi perspiciatis voluptatibus. Maiores iste magni ratione provident consequuntur illo ipsum, facilis eos delectus asperiores vitae, suscipit autem ea corporis dolorem explicabo architecto nam dolorum, officiis voluptates sit nihil doloremque! Animi rem, reiciendis doloribus blanditiis magni debitis rerum dolorem eius distinctio vero nostrum, possimus repellat quibusdam? Quasi quaerat maiores sed sapiente labore qui illum saepe similique repellendus, voluptatum autem sequi quibusdam, tempora debitis, quis a numquam obcaecati. Dolor culpa libero quod quaerat fugiat recusandae modi ipsum aliquam laborum quia in quibusdam facere a cumque neque inventore porro qui, nam alias similique vel sint odit.</p>
                  </div>
                  <div class="beefPart partMenu">
                    <p class="textHeader">Beef</p>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Numquam maxime quo aperiam voluptatum earum saepe? Incidunt, aliquam possimus ex corporis, tempora minima nobis, error dolorem consequatur exercitationem perspiciatis id perferendis sequi dolores voluptatum? Harum, tenetur nihil nulla sunt itaque reprehenderit blanditiis ut vitae deleniti, architecto deserunt. Magnam maiores, laboriosam autem, voluptatibus ut, ullam in quis officiis molestiae perferendis nulla. Placeat, ratione. Inventore saepe quasi numquam corrupti alias enim vitae atque quisquam maiores ducimus. Cumque quidem nulla aperiam quaerat! Sequi enim voluptate veniam ipsam vero. Nemo aut nulla distinctio aperiam iste ut, odit libero facere eum, incidunt sunt labore aliquid ipsam eveniet rerum iure deleniti nihil ad reiciendis, voluptas ex. Error vero debitis impedit. Explicabo sapiente commodi, fugit facilis molestiae iste sit suscipit ex quo impedit, atque hic? Fugit natus incidunt qui magnam ea sed molestias provident vel dolore soluta. Ipsam totam id ut iste! Est, laborum provident non aspernatur a ut iure sit nesciunt laudantium dignissimos eos dolore nostrum officia natus incidunt blanditiis voluptas similique. Enim asperiores voluptas autem vero dolorum nam vel ipsum non eum ut et facilis, aperiam magni suscipit iusto neque at! Iusto accusamus provident quisquam qui enim assumenda perferendis, hic, nam aperiam recusandae ad est, eveniet velit. Ab architecto eaque non. Numquam optio saepe, ea eligendi cupiditate beatae? Animi sint nesciunt odio aliquid aut obcaecati dolor? Quibusdam nemo fugiat quaerat consectetur corrupti. Officiis, temporibus reiciendis amet natus ab vitae omnis, excepturi eum assumenda, eveniet quibusdam quis veniam nostrum id? Possimus dolor quos vero aspernatur ullam saepe non eligendi quasi perferendis ea? Ullam earum consectetur cupiditate! Unde architecto veniam amet est at modi optio quo commodi autem ab quae beatae reiciendis, suscipit, iusto animi inventore. Est quibusdam tenetur cumque dolore inventore? Aliquid eos sed maiores delectus. Rerum, accusamus facilis aspernatur voluptas animi maiores ad optio vel pariatur labore hic laborum a numquam quibusdam fugit iste quos odio ullam distinctio ab libero nam officia aliquam. Nostrum a quas debitis omnis maiores iste vitae neque dignissimos dolore, necessitatibus autem quisquam aliquid delectus id, voluptates suscipit praesentium impedit? Mollitia fugiat, molestiae laudantium eos consectetur numquam commodi impedit, corporis voluptate voluptatem, cumque dignissimos rerum iste facere fuga consequatur. Aut ad dolore qui rem at quisquam eaque. Consectetur quod vitae quisquam. Impedit velit optio omnis at? Vitae nostrum, quia quasi nihil ad autem accusantium nam recusandae eum odio quidem. Ab, at doloribus. Laborum modi commodi non? Recusandae, quae! Architecto optio nemo quos.</p>
                  </div>
                  <div class="sushiPart partMenu">
                    <p class="textHeader">Sushi</p>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid pariatur inventore, vitae ad corporis tempore ullam officiis nihil error. Repudiandae illum nihil officiis maxime rerum molestiae ipsam quisquam maiores harum, non libero voluptas asperiores magni at magnam optio, aliquid obcaecati corporis tenetur veniam dicta fuga dignissimos natus illo. Earum saepe minus enim optio! Aperiam dolor quis architecto, velit maxime mollitia quia. Esse, optio quam? Veritatis rerum necessitatibus natus magnam earum qui harum, dignissimos expedita. Nemo et nam, dolorem totam cupiditate accusantium pariatur fugit officiis enim, aspernatur reprehenderit sapiente ut eius, praesentium quos natus expedita veniam! Debitis consequuntur inventore eligendi eius quasi voluptas repudiandae error, minima excepturi consequatur. Alias corrupti corporis hic reiciendis rem quis voluptates laborum totam amet inventore fugiat, temporibus quia necessitatibus esse! Tempora excepturi in quae atque facere, eos vitae voluptatem, autem beatae ipsa unde quasi eligendi numquam harum explicabo officiis aliquam quos, sint illo. Sapiente laboriosam consequatur laudantium cumque, quaerat, accusamus non aperiam, iste expedita repellat eveniet possimus tempora illum repellendus enim! Odit earum doloribus, vero at consequuntur sequi molestias architecto dignissimos reiciendis accusamus pariatur totam illo incidunt. Nam natus eius quam minima laudantium cupiditate molestiae eveniet amet quo rerum in delectus, cumque, expedita veritatis vel illo ea porro numquam accusantium corrupti minus, dignissimos consequatur quia. Cupiditate nesciunt minus odio ratione modi accusantium aliquid totam nisi unde debitis expedita a delectus iste in, necessitatibus ipsum ut! Sequi excepturi amet sunt veniam ut, laboriosam eveniet pariatur vero necessitatibus! Quibusdam nobis dignissimos error animi nostrum placeat totam a repudiandae excepturi minus maxime quam quasi modi, quos maiores mollitia ex cum nam quas, fuga exercitationem laudantium amet aspernatur. Nesciunt cum quis minima corporis totam cumque fugit odio est ea omnis aut dolorum, sapiente repellat minus eius deleniti excepturi, incidunt nostrum sequi! Dolore, in, aut aspernatur voluptas voluptatem voluptates sapiente ex possimus unde itaque, quis consequatur aliquid porro placeat ipsam eius. Error, sit ratione. Consequatur debitis harum, delectus quia in numquam ea perferendis, ab deleniti a adipisci voluptatibus non obcaecati. Alias, mollitia veritatis. Inventore quisquam illum qui impedit incidunt aliquid obcaecati enim saepe. Exercitationem pariatur, dolorem, veniam delectus, nihil ea quam voluptates quia porro ut minima asperiores in corporis hic aut! Magni nostrum fugit esse unde similique quidem cupiditate suscipit voluptates officiis eligendi, inventore, quasi vero, maxime corrupti deserunt cum beatae nisi. Amet, dolorum repudiandae? Sequi aliquam blanditiis eum delectus rerum accusantium consectetur numquam obcaecati, molestiae in, dolorem eius, officiis natus. </p>
                  </div>
            </div>
        </div>
    </div>
</body>
</html>

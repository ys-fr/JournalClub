# Article 
This page introduce some papers, and post my memos and link to notebook.


<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous"></link>
<style>
    .md-tabs__link{ 
                color: white;
    };
</style>
<script>
    function card(link, image, title, context) {
        document.write(
            `<div class="card" href=` + link + `>
            <img src=` + image + ` class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">` + title + `</h5>
                <p class="card-text">` + context + `.</p>
                <a   href=` + link + `><button type="button" class="btn btn-primary">Read</button></a>
            </div>
        </div>
        `);
    }
</script>

## Order book modeling
<div>
    <div class="card-deck">
    <script>card("Zovko-2002","LOB.png","Statistical analysis on order placement","")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    </div>


    <div class="card-deck">
    <script>card("/Draft/LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    </div>
</div>

# Japanese Draft 
The first author of this project, Yuki Sato, is Japanese. I, therefore, write a first draft of the theoretical and code description in Japanese. I post them here for Japanese users.


<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous"></link>
<style>
    .md-tabs__link{ 
                color: white;
    };
</style>
<script>
    function card(link, image, title) {
        document.write(
            `<div class="card" href=` + link + `>
            <img src=` + image + ` class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">` + title + `</h5>
                <a   href=` + link + `><button type="button" class="btn btn-primary">Read</button></a>
            </div>
        </div>
        `);
    }
</script>

## 高頻度ファイナンス
<div>
    <div class="card-deck">
    <script>card("RelativeLimitPrice","RelativeLimitPrice/LOB.png","相対価格","")</script>
    <script>card("AbsoluteLimitPrice","AbsoluteLimitPrice/LOB.png","絶対価格","")</script>
    <script>card("BidAskSpread","BidAskSpread/LOB.png","スプレッド","")</script>
    </div>


    <div class="card-deck">
    <script>card("PriceDuration/PriceDuration","LOB.png","Price duration","")</script>
    <script>card("VolumeDuration","LOB.png","Volume dration","")</script>
    <script>card("LevarageEffect","LOB.png","test","test")</script>
    </div>
</div>


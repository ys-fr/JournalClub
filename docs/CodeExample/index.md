# Code example 


<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous"></link>
<style>
    .md-tabs__link{ 
                color: white;
    };
</style>
<script>
    function card(link, image, title, context) {
        document.write(
            `<div class="card" href=https://github.com/ys-fr/JournalClub/blob/main/JupyterNotebook/` + link + `>
            <img src=` + image + ` class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">` + title + `</h5>
                <p class="card-text">` + context + `.</p>
                <a   href=https://github.com/ys-fr/JournalClub/blob/main/JupyterNotebook/` + link + `><button type="button" class="btn btn-primary">Read</button></a>
            </div>
        </div>
        `);
    }
</script>

## Stylized facts
<div>
    <div class="card-deck">
    <script>card("StylizedFacts/IntradaySeasonality_NumTransactions/Python.ipynb","StylizedFacts/Intraday_Spread.png","The intraday seasonality of the bid-ask spread","")</script>
    <script>card("StylizedFacts/IntradaySeasonality_NumTransactions/Python.ipynb","StylizedFacts/Intraday_transactions.png","The intraday seasonality of the number of transactions","")</script>
    <script>card("StylizedFacts/IntradaySeasonality_NumTransactions/Python.ipynb","StylizedFacts/Intraday_transactionvol.png","The intraday seasonality of the transaction volume","")</script>
    </div>


    <div class="card-deck">
    <script>card("StylizedFacts/LongMemory_Spread/Python.ipynb","StylizedFacts/LongMemory_spread.png","The long memory property of the spread", "")</script>
    <script>card("StylizedFacts/LongMemory_MO/Python.ipynb","StylizedFacts/LongMemory_MO.png","The long memory property of the order flow", "")</script>
    <script>card("StylizedFacts/TransactionVolume_MO/Python.ipynb","StylizedFacts/TransactionVolume_MO.png","The distribution of the transaction volume", "")</script>
    </div>


    <div class="card-deck">
    <script>card("StylizedFacts/Duration_CO/Python.ipynb","StylizedFacts/Duration_CO.png","The distribution of the interval between the limit order submission and the cancellation", "")</script>
    <script>card("StylizedFacts/LO_size/Python.ipynb","StylizedFacts/LO_size.png","The limit order size distribution", "")</script>
    <script>card("StylizedFacts/BidAskBounce/Python.ipynb","StylizedFacts/BidAskBounce.png","Bid-Ask Bounce", "")</script>
    </div>
</div>

## Price impact
<div>
    <div class="card-deck">
    <script>card("StylizedFacts/LongMemory_Spread/Python.ipynb","LongMemory_spread.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    </div>


    <div class="card-deck">
    <script>card("/Draft/LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    </div>
</div>

## Optimal execution
<div>
    <div class="card-deck">
    <script>card("/Draft/LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    </div>


    <div class="card-deck">
    <script>card("/Draft/LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    </div>
</div>

## LOB dynamics
<div>
    <div class="card-deck">
    <script>card("/Draft/LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    </div>


    <div class="card-deck">
    <script>card("/Draft/LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    </div>
</div>

## Other materials
<div>
    <div class="card-deck">
    <script>card("/Draft/LevarageEffect","material/LOB12.png","Numerical generation of the long memory series","")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","")</script>
    </div>


    <div class="card-deck">
    <script>card("/Draft/LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    <script>card("LevarageEffect","material/LOB12.png","test","test")</script>
    </div>
</div>
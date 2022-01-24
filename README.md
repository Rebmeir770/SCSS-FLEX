# SCSS-FLEX
 scss-flex מטלה
html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flex</title>
    <link rel="stylesheet" href="dist/style.css">
</head>
<body>
    <div class="wrapper">
        <div class="Barr">
            <h2>ESPN</h2>
               <p>in your face</p>
        </div>
        <div class="cards">

            
            <div class="card">
                <img src="https://a4.espncdn.com/combiner/i?img=%2Fphoto%2F2022%2F0117%2Fr962777_608x342_16%2D9.jpg&w=272&h=153&scale=crop&cquality=80&location=origin">
                <img class="icon" src="espn.png"icon">
            <h2>PGA Tour action expands to four feeds this week at The American Express. Here is how to watch on ESPN+.</h2>
            </div>

            
            <div class="card">
                <img src="https://a3.espncdn.com/combiner/i?img=%2Fphoto%2F2022%2F0109%2Fr959346_608x342_16%2D9.jpg&w=272&h=153&scale=crop&cquality=80&location=origin">
                <img class="icon" src="espn.png" alt="icon">
                <h2>The first major tennis tournament of the 2022 calendar year is the Australian Open. Here's how you can watch all of the action.</h2>
            </div>

            
            <div class="card">
                <img src="https://a2.espncdn.com/combiner/i?img=%2Fphoto%2F2022%2F0118%2Fnfl_kiper_mock%2Ddraft_16x9.png&w=272&h=153&scale=crop&cquality=80&location=origin">
                <img class="icon" src="espn.png" alt="icon">
                <h2>Mel Kiper Jr. projects Round 1 of April's draft, filling needs for every team. Where will the first quarterback land?</h2>
            </div>

           
            <div class="card">
                <img src="https://a4.espncdn.com/combiner/i?img=%2Fphoto%2F2020%2F1124%2Fr780056_608x342_16%2D9.jpg&w=272&h=153&scale=crop&cquality=80&location=origin">
                <img class="icon" src="espn.png" alt="icon">
                <h2>Brady's achievements at his age have been exhaustively recorded. Yet it's still staggering that he's older than the coaches of the Green Bay Packers, Los Angeles Rams and San Francisco 49ers. And he has history with all three.</h2>
            </div>

        </div>
    </div>

</body>
</html>
                                                           
SCSS:
                                                           
.wrapper {
    
    display: flex;
    flex-direction: column;
    margin: auto;
    padding: 0;
    box-sizing: border-box;
    margin-top: 40px;   
    


    h2 {
        direction: ltr;
        font-size: 18px;
        
    }

    .Barr {

        height: 30px;
        background-color: red;
        color: white;
        display: flex;
        justify-content: space-between;
        flex-direction: initial;
        align-items: center;
        padding: 0 10px;
        position: relative;
        margin-bottom: 15px;
    }

    .cards {
        display: flex;
        flex-direction: row-reverse;
        margin: auto;
        position: relative;
        



        .card {
            margin-left: 16px;
            display: flex;
            flex-direction: column;
            

            .icon {
                width: 35px;
                height: 35px;
                position: relative;
                left: 80%;
                bottom: 34px;
                
            }

            h2 {
                margin-top: 0;
            }
        }

        
        
    }

}

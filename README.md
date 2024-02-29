# fitness-and-sports
ideas that can boost fitness activities and assist in keeping fit
FITNESS.HTML,
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Freak</title>
    <link rel="stylesheet" href="aditya.css">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css">
</head>

<body>

    <div class="header">
        <div class="bar" onclick="bars()">
            <div class="lines">
                <div class="first line"></div>
                <div class="second line"></div>
                <div class="third line"></div>
            </div>
        </div>
        <div class="logo">
            FITNESS FREAK
        </div>
        <div class="nav">
            <a href="#">HOME</a>
            <a href="#">ABOUT US</a>
            <a href="#">PAGES</a>
            <a href="#">CONTACT US</a>
        </div>
        <div class="search">
            <a href="#" onclick="searchTab()"><i class="fa fa-search" aria-hidden="true"></i></a>
        </div>
        <div class="bell">
            <i class="fa fa-bell" aria-hidden="true"></i>
        </div>
        <div class="profile">
            <img src="aditya.jpg" alt="">
        </div>
        <div class="search-tab">
            <form>
                <input type="text" placeholder="Search....">
            </form>
        </div>
    </div>
    <div class="banner">
        <video id="videoPlay" loop="true" autoplay="true" muted>
            <source src="SnapInsta.io-Sam Sulek X The Lost Soul Down _ Gym Motivation Edit-(1080p).mp4">
        </video>
    </div>
    <div class="first-content">
        <div class="pain-gain">
            <div class="no-pain">
                NO PAIN
            </div>
            <div class="no-gain">
                NO GAIN
            </div>
        </div>
        <div class="right-first">
            <div class="opacity-body">

            </div>
        </div>
    </div>
    <div class="build-muscle">
        <div class="content-back">
            GAIN STRENGTH,
            <br>
            BUILD MUSCLE,
            <br>
            SHRED BODY FAT.
            <br>
            <p> We'll Help You Track Your Fitness And Plan Your Daily Workout.</p>
            <!-- <br> -->
            <button>Know More</button>
        </div>
    </div>
    <div class="login">
        <div class="log-color">
            <form>

                <input type="text" placeholder="Enter Your Name" name="nn"><br>
                <output name="ki"></output>
                <br>
                <input type="text" name="hehe" placeholder="Enter Your Phone No."><br>
                <output name="ki3"></output>
                <br>
                <input type="password" name="io" placeholder="Enter Your password"><br>
                <output name="ki2"></output>
                <br>
                <input type="password" name="io2" placeholder="Confirm password"><br>
                <output name="ki4"></output>
                <br>
                <label><input type="radio" name="ui"> Male</label>
                <label><input type="radio" name="ui"> Female</label>
                <br>
                <output name="ki5"></output>
                <br>

                <select name="course" id="">
                    <option value=""> Choose Your Membership </option>
                    <option>1 Month</option>
                    <option>2 Month</option>
                    <option>3 Month</option>
                    <option>6 Month</option>
                    <option>12 Month</option>
                    <option>15 Month</option>
                </select>
                <br>
                <output name="ki9"></output>
                <br>


                <input type="submit">
            </form>
        </div>
    </div>

    <script src="aditya.js"></script>
</body>

</html>
FITNESS.CSS,
* {
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
    color: white;
}

@font-face {
    font-family: oldSchool;
    src: url(font/VarsityTeam-Bold.otf);
}

html {
    background-color: black;
}

::-webkit-scrollbar {
    display: none;
}

/* body {
    width: 100%;
    overflow-x: hidden;
} */

a {
    text-decoration: none;
    color: white;
}

.header {
    height: 80px;
    width: 100%;
    background-color: transparent;
    color: white;
    position: relative;
    z-index: 100000;
    top: 0%;
}

.bar {
    float: left;
    width: 5%;
    height: 100%;
    padding-left: 10px;
}

.lines {
    height: 30px;
    width: 30px;
    margin: auto;
    align-items: center;
    margin-top: 25px;
    transition: all 0.2s linear;
}

.line {
    height: 2px;
    width: 100%;
    background-color: white;
    margin-bottom: 10px;
    transition: all 0.2s 0.3s linear;
}

.logo {
    float: left;
    width: 25%;
    letter-spacing: 5px;
    font-weight: 100;
    font-size: 30px;
    padding-left: 30px;
    padding-top: 22px;
    height: 100%;
}

.nav {
    float: left;
    height: 100%;
    width: 55%;
    padding-top: 28px;
    padding-left: 55px;
}

.nav a {
    margin-left: 25px;
    font-size: 18px;
    padding-bottom: 5px;
}

.nav a:hover {
    border-bottom: 1px white solid;
}

.search-tab {
    position: absolute;
    top: 58px;
    z-index: 10000;
    width: 100%;
    right: -50%;
    display: none;
}

.search-tab input {
    width: 250px;
    height: 25px;
    background-color: white;
    padding-left: 18px;
    font-size: 12px;
    margin-left: 220px;
    border-radius: 10px;
    border: #56565b;
    color: black;
}

.bell {
    float: left;
    width: 4%;
    height: 100%;
    text-align: right;
}

.bell i {
    font-weight: 800;
    font-size: 14px;
    padding-top: 32px;
    padding-right: 18px;
}


.search {
    text-align: center;
    height: 100%;
    width: 4%;
    float: left;
}

.search i {
    font-weight: 800;
    font-size: 14px;
    padding-top: 32px;
    padding-right: 18px;
}

video {
    width: 100%;
    height: 100vh;
    object-fit: cover;
    position: absolute;
    top: 0;
    opacity: 0.8;
}

.profile {
    float: left;
    height: 50%;
    margin-top: 18px;
    margin-left: 20px;
}

.profile img {
    height: 100%;
    width: 100%;
    border-radius: 50%;
}

.first-content {
    clear: both;
    position: relative;
    top: 100vh;
    width: 100%;
    height: 350px;
}

.pain-gain {
    width: 50%;
    font-family: oldSchool;
    font-size: 100px;
    letter-spacing: 10px;
    float: left;
    padding-left: 50px;
}

.no-pain {
    margin-bottom: 110px;
}

.right-first {
    height: 100%;
    float: right;
    width: 30%;
    margin: 10%;
    background-image: url(body\ img.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: bottom;
    border: 2px white solid;
    border-radius: 20px;
    margin-top: 0;
}

.opacity-body {
    height: 100%;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.393);
}

.build-muscle {
    height: 500px;
    clear: both;
    width: 100%;
    margin-top: 700px;
    background-image: url(back.webp);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    margin-bottom: 70px;
}

.content-back {
    height: 100%;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.217);
    text-align: right;
    font-weight: 600;
    font-size: 55px;
    line-height: 80px;
    padding-right: 20px;
    padding-top: 70px;
}

.content-back p {
    font-size: 25px;
}

.content-back button {
    color: black;
    width: 170px;
    background-color: rgb(230, 204, 173);
    height: 40px;
    font-size: 16px;
    margin-right: 90px;
    border-radius: 20px;
    transition: all 0.25s linear;
    font-weight: 600;
}

.content-back button:hover {
    color: white;
    background-color: transparent;
    border: 2px white solid;
}
.login{
    height: 600px;
    width: 100%;
    background-image: url(log.avif);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: bottom;
    margin-bottom: 50px;
    padding-top: 100px;
}
.log-color{
    height: 100%;
    width: 100%;
    background-color: rgba(0, 0, 0, 0);
}
form {
    text-align: center;
    backdrop-filter: blur(15px);
    width: 23%;
    border-radius: 10px;
    margin: auto;
    padding: 40px 0px;
    color: black;
}
input
{
    border: 0px;
    height: 25px;
    border-radius: 5px;
    color: black;
}
select{
    color: black;
}
SPORTS
LOGIN.HTML
<!DOCTYPE html>
<html>
<body>

<h2>Login Page</h2>

<form action="/submit_login" method="post">
  <label for="username">Username:</label><br>
  <input type="text" id="username" name="username"><br>
  <label for="password">Password:</label><br>
  <input type="password" id="password" name="password"><br>
  <input type="submit" value="Submit">
</form>

<p>Don't have an account? <a href="index.html">Sign up here</a>.</p>

</body>
</html>
INDEX.HTML,
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sports Leagues</title>
    <link rel="stylesheet" href="new.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        /* Add your CSS styles here */
    </style>
</head>
<body>
    <header>
        <h1>Sports League Management</h1>
        <img src="data:image/jpeg;base64,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" alt="">
    </header>

    <nav>
        <button id="IplDataBtn"><a href="crick.html">Indian primier League</a></button>
        <button id="IccDataBtn"><a href="ICC.html">World Cup</a></button>
        <button id="BblDataBtn"><a href="bbl.html">Bash League</a></button>
        <button id="IaT20DataBtn"><a href="T20.html">Ind Vs Aus T20</a></button>
        <button id="PklDataBtn"><a href="pkl.html">Pro Kabaddi League</a></button>
    </nav>
 
    <main>
        <div id="leagueData"></div>
    </main>

    <footer>
        <p>&copy; 2024 Your League Name</p>
    </footer>

    <script>
        // Mock data for demonstration purposes
        const leagueData = {
            teams: [
                { name: 'Team A', points: 10 },
                { name: 'Team B', points: 8 },
                { name: 'Team C', points: 9 },
                { name: 'Team D', points: 10},
                { name: 'Team E', points: 7},
                { name: 'Team F', points: 9},
                // Add more teams as needed
            ],
            matches: [
                { homeTeam: 'Team A', awayTeam: 'Team B', result: '2-1' },
                // Add more matches as needed
            ],
        };

        // Function to load and display league data
        function loadLeagueData() {
            const leagueDataDiv = document.getElementById('leagueData');

            // Clear previous data
            leagueDataDiv.innerHTML = '';

            // Display teams
            leagueData.teams.forEach(team => {
                const teamDiv = document.createElement('div');
                teamDiv.textContent = ${team.name} - Points: ${team.points};
                leagueDataDiv.appendChild(teamDiv);
            });

            // Display matches
            leagueData.matches.forEach(match => {
                const matchDiv = document.createElement('div');
                matchDiv.textContent = ${match.homeTeam} vs ${match.awayTeam} - Result: ${match.result};
                leagueDataDiv.appendChild(matchDiv);
            });
        }

        // Event listener for the load data button
        const loadDataBtn = document.getElementById('loadDataBtn');
        loadDataBtn.addEventListener('click', loadLeagueData);

        // You would typically fetch data from a server instead of using mock data
    </script>
</body>
</html>
CRICK.HTML,
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Hardik returns to MI, Cameron Green moves to RCB</h1>
    <img src="https://www.cricbuzz.com/a/img/v1/595x396/i1/c361637/hardik-pandya-won-four-ipl-tit.jpg" alt="">
    <p>The much-anticipated transfer of Hardik Pandya to Mumbai Indians has been successfully completed. In a noteworthy one-way, all-cash transaction, the 30-year-old all-rounder has officially returned to the franchise he won four titles with.

        Simultaneously, Mumbai Indians have bolstered their financial position to afford the Pandya acquisition by trading Cameron Green to Royal Challengers Bangalore in another all-cash transaction to the tune of INR 17.5 crore, the league value of the Australian all-rounder.
        
        This financial maneuver not only facilitates the completion of the Pandya trade with Gujarat Titans but also positions the five-time champions with substantial resources for the upcoming IPL 2024 auction scheduled to take place in Dubai on December 19.</p>
    <h2>TATA IPL 2023, Final CSK Vs GT - Match Report</h2>away just three in the 12th over but Dube finally found the middle of the bat as he thumped two sixes in a row to end the over on a high and amass 15 runs. Rayudu, playing his last IPL match, joined the party as he smacked the first ball of the 13th over from Mohit over long off for a six and then cracked a four off the next ball through extra cover, then thumped another six but Mohit hit back hard to have him caught and bowled off the next ball and then got the huge wicket of MS Dhoni off he next ball as he had him caught at extra cover. The roller-coaster saw 17 runs scored and two wickets taken as the equation came down to 21 needed off 12.Shami bowled a very good penultimate over to give away just eight. With 13 needed off the last over, the experienced Mohit nailed four yorkers upfront and gave away just three runs. With 10 needed off two, the tables turned again as Mohit missed his marker and Jadeja smacked a six over long on. With four needed off the last ball, Mohit bowled a low full toss down the leg side and Jadeja swiped it to fine leg for a four to win it for CSK and spark wild celebrations.Earlier, Chennai Super Kings captain MS Dhoni won the toss and elected to bowl. They made one change to the starting line-up as Matheesha Pathirana replaced Shivam Dube. The four-time champions named Shivam Dube, Mitchell Santner, Subhranshu Senapati, Shaik Rasheed and Akash Singh as their substitutes.Gujarat Titans named an unchanged eleven. Josh Little, KS Bharat, Odean Smith, Sai Kishore and Shivam Mavi made it to their substitutes list.Chennai Super Kings started off well as they bowled with discipline and accuracy and could have had both the openers back in the hut inside the Powerplay. The four-time champions didn't give away any boundaries in the first two overs. And they could have had the in-form Shubman Gill back in the hut in as early as the second over but Deepak Chahar dropped one at backward square leg as Gill flicked one uppishly straight to the CSK pacer off Tushar Deshpande.Wriddhiman Saha then opened up in the next over as he flicked one for a six and heaved the next for a four and then lofted one over cover to make it 16 off the Chahar over. Gill then joined the party as he made CSK pay for the drop with three delightful fours off Deshpande: A short arm Jab through mid-wicket, a flick through mid-wicket and a stand and deliver extra cover drive. Saha then got a bit lucky in the next over as he hit one uppishly straight back to Chahar who couldn't hold on to a tough chance off his own bowling.MS Dhoni then introduced spin via Maheesh Theekshana in the sixth over and Gill went after him straightaway, cracking three fours in a row to take GT to 62/0 at the end of the Powerplay.Saha then got lucky not once but twice as he survived two run-out chances but then MS Dhoni provided a moment of brilliance as he sent back the dangerous Gill via lightning fast glovework to have him stumped off Ravindra Jadeja in the same over.Jadeja helped CSK claw their way back as they kept things tight and gave away just 24 in the next four overs as GT reached 86/1 at the halfway mark.Sai Sudharsan then provided some relief with a couple of well-placed fours through the off side, off Matheesha Pathirana as GT took 13 from the over. Saha then reached his fifty off 36 balls with a four off Jadeja and Sudharsan followed it up with a six over mid-wicket.Dhoni brought back Chahar in the 14th over and the CSK pacer broke the 65-run stand as he had Saha caught behind off a slower ball as Saha (54 off 39) top-edged his pull off a leg cutter. That wicket didn't deter Sudharsan though as he went on the counter-attack and hit a couple of sixes off Theekshana in the next over. He brought up his third fifty of the season as he cracked one through backward point for a four off Pathirana. He followed it up with a flicked four wide of mid on to make it 10 off the over. Sudharsan then went berserk in the next over off Deshpande, hitting three fours and a six to amass 20 runs off it. Pathirana balanced things out slightly by not conceding a boundary and giving away nine off the 18th over.Captain Pandya and Sudharsan then took on Deshpande in the penultimate over, cracking a couple of sixes and a four to amass 18 off the over and take GT to 200. Sudharsan started the final over with two superb sixes but departed four short of his century off the next ball as he was trapped LBW by Pathirana. He reviewed it but the Ball Tracking replays showed all three reds. The youngster walked off to a standing ovation for his magnificent innings. Pathirana then removed Rashid Khan off the last ball as Gujarat Titans took 14 off the last over and posted 214/4.Gujarat Titans introduced Josh Little as their Impact Player, replacing Sai Sudharsan at the start of the second innings.Brief Scores: Chennai Super Kings 171/5 (Devon Conway 47, Shivam Dube 32*; Mohit Sharma 3/36)  beat Gujarat Titans 214/4 (Sai Sudharsan 96, Wriddhiman Saha 54; Matheesha Pathirana 2/44) by 5 wickets (DLS Method) " alt="">
    <img src="https://crickettimes.com/wp-content/uploads/2023/11/CSK-team-members-celebrating-fifth-IPL-triumph.webp" alt="">
    <p>Ravindra Jadeja provided a grandstand finish, hitting a six and a four with 10 needed off the last two balls, to power Chennai Super Kings to their fifth IPL title as they beat defending champions Gujarat Titans by five wickets (DLS Method) in a thriller at the Narendra Modi Stadium in Ahmedabad.Jadeja smashed 15* off 6 balls as a collection of cameos from Devon Conway (47 off 25), Ruturaj Gaikwad (26 off 16), Shivam Dube (32* off 21). Ajinkya Rahane (27 off 13) and Ambati Rayudu (19 off 8) helped CSK chase down 171 from 15 overs in a rain-shortened IPL final.Earlier, Sai Sudharsan had put on a stunning show on the big stage with a splendid 96 off 47 balls, ably supported by Wriddhiman Saha (54 off 39) and Shubman Gill 39 (20) to help GT post a mammoth 214/4 before rain forced the match to be shortened to 15 overs.  Chasing 171 from 15 overs, Ruturaj Gaikwad and Devon Conway got CSK off to a flier. Ruturaj got off the mark in style with a lovely square drive for a four off the third ball of the innings from Mohd. Shami. But soon after rain stopped play and the match was reduced to 15-overs with CSK having to chase a revised target of 171 runs. The revised playing conditions meant the Powerplay was reduced to four overs while a bowler could bowl a maximum of three overs.As play resumed, Gaikwad cracked another four in the unfinished first over as he pulled one through backward square leg to make it 10 runs off it. Devon Conway then got going straightaway as he lofted one over extra cover for a six off Hardik Pandya in the second over and then whipped one to fine leg for a four. He took the attack to Shami in the next over, smacking two more fours to accumulate 11 off it.Hardik Pandya introduced Rashid Khan early into the attack but the CSK batters went after him straightaway, cracking a couple of fours and a six to take CSK to 52/0 at the end of the Powerplay (4th over).Noor Ahmad bowled a good first over, giving away just six but Josh Little's first over went for 14 as Conway thumped a pull over deep mid-wicket off the last ball of the sixth over.The impressive Noor got the much-needed breakthrough for GT as he broke the 74-run opening stand by sending back Gaikwad (26 off 16) via a wrong'un. CSK then sent out Shivam Dube as their Impact Player, at No.3, replacing Matheesha Pathirana. Noor struck again off the final ball of the over to have Conway (47 off 25) caught at long off to peg CSK back.Ajinkya Rahane arrived and got going in style with two exquisite sixes off Josh Little to make it a 16-run over. Noor Ahmad though balanced things out with another brilliant over, giving away just five as he finished with impressive figures of 3-0-17-2.Rahane got the momentum back again with a couple of fours off Rashid to bring the equation down to 60 needed off 30. 
 
Mohit Sharma arrived into the attack in the 11th over and struck straightaway to get the crucial wicket of Rahane (27 off 13), caught a deep point off a slower one. The GT pacer bowled a fantastic over and gave away just six as the equation came to 53 needed off 24 balls. 
 
Rashid bowled four good balls, giving away just three in the 12th over but Dube finally found the middle of the bat as he thumped two sixes in a row to end the over on a high and amass 15 runs. Rayudu, playing his last IPL match, joined the party as he smacked the first ball of the 13th over from Mohit over long off for a six and then cracked a four off the next ball through extra cover, then thumped another six but Mohit hit back hard to have him caught and bowled off the next ball and then got the huge wicket of MS Dhoni off he next ball as he had him caught at extra cover. The roller-coaster saw 17 runs scored and two wickets taken as the equation came down to 21 needed off 12.Shami bowled a very good penultimate over to give away just eight. With 13 needed off the last over, the experienced Mohit nailed four yorkers upfront and gave away just three runs. With 10 needed off two, the tables turned again as Mohit missed his marker and Jadeja smacked a six over long on. With four needed off the last ball, Mohit bowled a low full toss down the leg side and Jadeja swiped it to fine leg for a four to win it for CSK and spark wild celebrations.Earlier, Chennai Super Kings captain MS Dhoni won the toss and elected to bowl. They made one change to the starting line-up as Matheesha Pathirana replaced Shivam Dube. The four-time champions named Shivam Dube, Mitchell Santner, Subhranshu Senapati, Shaik Rasheed and Akash Singh as their substitutes.Gujarat Titans named an unchanged eleven. Josh Little, KS Bharat, Odean Smith, Sai Kishore and Shivam Mavi made it to their substitutes list.Chennai Super Kings started off well as they bowled with discipline and accuracy and could have had both the openers back in the hut inside the Powerplay. The four-time champions didn't give away any boundaries in the first two overs. And they could have had the in-form Shubman Gill back in the hut in as early as the second over but Deepak Chahar dropped one at backward square leg as Gill flicked one uppishly straight to the CSK pacer off Tushar Deshpande.Wriddhiman Saha then opened up in the next over as he flicked one for a six and heaved the next for a four and then lofted one over cover to make it 16 off the Chahar over. Gill then joined the party as he made CSK pay for the drop with three delightful fours off Deshpande: A short arm Jab through mid-wicket, a flick through mid-wicket and a stand and deliver extra cover drive. Saha then got a bit lucky in the next over as he hit one uppishly straight back to Chahar who couldn't hold on to a tough chance off his own bowling.MS Dhoni then introduced spin via Maheesh Theekshana in the sixth over and Gill went after him straightaway, cracking three fours in a row to take GT to 62/0 at the end of the Powerplay.Saha then got lucky not once but twice as he survived two run-out chances but then MS Dhoni provided a moment of brilliance as he sent back the dangerous Gill via lightning fast glovework to have him stumped off Ravindra Jadeja in the same over.Jadeja helped CSK claw their way back as they kept things tight and gave away just 24 in the next four overs as GT reached 86/1 at the halfway mark.Sai Sudharsan then provided some relief with a couple of well-placed fours through the off side, off Matheesha Pathirana as GT took 13 from the over. Saha then reached his fifty off 36 balls with a four off Jadeja and Sudharsan followed it up with a six over mid-wicket.Dhoni brought back Chahar in the 14th over and the CSK pacer broke the 65-run stand as he had Saha caught behind off a slower ball as Saha (54 off 39) top-edged his pull off a leg cutter. That wicket didn't deter Sudharsan though as he went on the counter-attack and hit a couple of sixes off Theekshana in the next over. He brought up his third fifty of the season as he cracked one through backward point for a four off Pathirana. He followed it up with a flicked four wide of mid on to make it 10 off the over. Sudharsan then went berserk in the next over off Deshpande, hitting three fours and a six to amass 20 runs off it. Pathirana balanced things out slightly by not conceding a boundary and giving away nine off the 18th over.Captain Pandya and Sudharsan then took on Deshpande in the penultimate over, cracking a couple of sixes and a four to amass 18 off the over and take GT to 200. Sudharsan started the final over with two superb sixes but departed four short of his century off the next ball as he was trapped LBW by Pathirana. He reviewed it but the Ball Tracking replays showed all three reds. The youngster walked off to a standing ovation for his magnificent innings. Pathirana then removed Rashid Khan off the last ball as Gujarat Titans took 14 off the last over and posted 214/4.Gujarat Titans introduced Josh Little as their Impact Player, replacing Sai Sudharsan at the start of the second innings.Brief Scores: Chennai Super Kings 171/5 (Devon Conway 47, Shivam Dube 32*; Mohit Sharma 3/36)  beat Gujarat Titans 214/4 (Sai Sudharsan 96, Wriddhiman Saha 54; Matheesha Pathirana 2/44) by 5 wickets (DLS Method) </p>
    <h3></h3>
</body>
</html><title>IPL Schedule</title>
<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }
  th, td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
  }
  th {
    background-color: #f2f2f2;
  }
</style>
</head>
<body>

<h2>IPL 2023 Schedule</h2>

<table>
<tr>
  <th>Date</th>
  <th>Match</th>
  <th>Venue</th>
</tr>
<tr>
  <td>April 5, 2023</td>
  <td>Team A vs Team B</td>
  <td>Stadium 1</td>
</tr>
<tr>
  <td>April 7, 2023</td>
  <td>Team C vs Team D</td>
  <td>Stadium 2</td>
</tr>
<!-- Add more rows for other matches -->
</table>
BBL.HTML,
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Big Bash League</h1>
    <img src="https://upload.wikimedia.org/wikipedia/en/c/c0/Big_Bash_League_%28logo%29.png" alt="">
    <p>The Big Bash League (known as the KFC Big Bash League for sponsorship reasons, often abbreviated to BBL or Big Bash) is an Australian men's professional club Twenty20 cricket league, which was established in 2011 by Cricket Australia. The Big Bash League replaced the previous competition, the KFC Twenty20 Big Bash, and features eight city-based franchises instead of the six state teams which had participated previously. The competition has been sponsored by fast food-chicken outlet KFC since its inception. It was in 2016/17 one of the two T20 cricket leagues, alongside the Indian Premier League, to feature amongst the top ten domestic sport leagues in average attendance. The winner of BBL 12 (2022/2023) was the Perth Scorchers, who beat the Brisbane Heat by 5 wickets in the final.

        BBL matches are played in Australia during the summer, in December, January and February.
        
        Out of the eight teams in the tournament, six have won the title at least once. The Perth Scorchers are the most successful team in the league's short history, having won the title five times including consecutively for two years twice. The Sydney Sixers have won the title three times, including consecutively for two years. The other four teams that have won the title are the Adelaide Strikers, Melbourne Renegades, Brisbane Heat and Sydney Thunder.
        
        Before 2014, the top two teams in the tournament used to qualify for the Champions League Twenty20 tournament, which was an annual international Twenty20 competition played between the top domestic teams from various nations. The Champions League Twenty20 became defunct after its 2014 tournament.[1</p>
    <h2>Tournament format</h2>
    <p>Since the inception of the BBL in 2011, the tournament has followed the same format every year except the inaugural season.[19] The first BBL season had 28 group stage matches, before expanding to 32 in the following season.[11]

Since the 2018–19 season, each team plays all other teams twice during a season, for a total of 56 regular season matches before the finals series.

In previous seasons of the tournament, the group stage matches were divided into eight rounds, with four matches played in each round. Each team played six other teams once during a season, and one team twice. This allowed for both Sydney and Melbourne (which have two teams each) to play 2 derbies within a single season.[20] Each team played eight group stage matches, four at home and four away, before the top four ranked teams progressed to the semi-finals.[20] In the 2017/18 Season, the format changed so that there would be 40 group stage matches with each team playing 10 matches before the semi-finals.[21] The season was held over a similar time-frame thus resulting in more doubleheaders (one game afternoon, one game night) and teams playing more regularly.[22]

The final of the tournament is played at the home ground of the highest-ranked team. The only exception to this rule was 2014–15 season when the final was played at a neutral venue (Manuka Oval), due to the 2015 Cricket World Cup.[19][23]

In the 2018–19 season, the league introduced a 'bat flip' (instead of a coin toss) to decide who would bat/bowl first.[24]

The finals structure was changed in the 2019–20 season to include a fifth team. The structure was a hybrid version of the Page–McIntyre final four system with the addition of 'The Eliminator' being the difference between the original and hybrid versions.:

Eliminator – Fourth v Fifth
Qualifier – First v Second
Knock-Out – Third v Winner of the Eliminator
Challenger – Loser of the Qualifier v Winner of the Knock-Out
Final – Winner of the Qualifier v Winner of the Challenger</p>
<h3>Current teams</h3>
<p>The competition features eight city-based franchises, instead of the six state-based teams which had previously competed in the KFC Twenty20 Big Bash. Each state's capital city features one team, with Sydney and Melbourne featuring two. The team names and colours for all teams were officially announced on 6 April 2011.[25] The Melbourne Derby and Sydney Derby matches are some of the most heavily attended matches during the league and are widely anticipated by the fans.[26] The Scorchers and Sixers have also developed a rivalry between them over the years and their matches attract good crowds and TV ratings.[27]

    A single city-based franchise can have a maximum of 19 contracted players for a season, with the squad including a minimum of two rookie contracts and a maximum of six overseas players, although only three international players can play in each match from 2020 to 2021 edition. Each team can also have a maximum of two overseas replacement players, in case the original overseas players get injured or withdraw.[28]
    
    Team	Location	Home ground	Coach	Captain
    Adelaide Strikers	Adelaide, South Australia	Adelaide Oval	Jason Gillespie	Travis Head
    Brisbane Heat	Brisbane, Queensland	Brisbane Cricket Ground	Wade Seccombe	Usman Khawaja
    Hobart Hurricanes	Hobart, Tasmania	Blundstone Arena	Adam Griffith	Matthew Wade
    Melbourne Renegades	Melbourne, Victoria	Marvel Stadium	David Saker	Aaron Finch
    Melbourne Stars	Melbourne, Victoria	Melbourne Cricket Ground	David Hussey	Glenn Maxwell
    Perth Scorchers	Perth, Western Australia	Perth Stadium	Adam Voges	Ashton Turner
    Sydney Sixers	Sydney, New South Wales	Sydney Cricket Ground	Greg Shipperd	Moises Henriques
    Sydney Thunder	Sydney, New South Wales	Sydney Showground Stadium	Trevor Bayliss	Jason Sangha
    Rivalries
    Throughout the history of the tournament rivalries have been formed by competition between teams and by teams being in the same city.
    
    Sydney Smash
    The Sydney Smash is a game between the Sydney based teams, the Sydney Sixers and Sydney Thunder. This rivalry was started in the inaugural season due to both teams being from Sydney and being made up of New South Wales cricket team players. The Sixers have won 16 times to the Thunder's 7 but the game still attracts a large crowd for every game.
    
    Melbourne Derby
    The Melbourne Derby takes place between the two Melbourne based teams, the Melbourne Renegades and the Melbourne Stars. This derby is similar in nature to the Sydney Smash as the cores of both teams come from the Victoria cricket team and has been happening since the inaugural season of the competition. In BBL05 the game drew the largest crowd for a Big Bash game with 80,883 fans attending the game at the MCG.[29]
    
    Perth Scorchers - Sydney Sixers
    The Scorchers/Sixers rivalry has developed over the competition's 12 seasons due to their unparalleled success. The Scorchers have won the title five times and Sixers have claimed the trophy three times. No other team has been champions more than once. The Scorchers and the Sixers have both been runners up three times. They've met in the final on five occasions. The Scorchers have won three of those encounters and the Sixers two.[30]
    
    Tournament season and results
    Perth Scorchers have won five titles and Sydney Sixers three.[31] Both of these teams have won the title in consecutive seasons.[32]
    
    The Scorchers have reached the final of the tournament eight times. Out of the eight teams in the tournament, six have won the title at least once. Only two other teams (Hobart Hurricanes and Melbourne Stars) have reached the final at least twice[33] The other four teams which have won the title once are the Brisbane Heat in the second season (2012–13), the Sydney Thunder in (2015–16),[34][35] the Adelaide Strikers in (2017–18),[36] and the Melbourne Renegades in (2018–19).[37][38]
    
    The WACA Ground has hosted the final on four occasions, the most of any venue.
    
    Finals sumamary
    Season	Final	Final host	Final venue	City/Town	Attendance
    Winner	Result	Runner-up
    2011–12
    Details	Sydney Sixers
    3/158 (18.5 overs)	Sixers won by 7 wickets
    Scorecard	Perth Scorchers
    5/156 (20 overs)	Perth Scorchers	WACA Ground	Perth	16,255
    2012–13
    Details	Brisbane Heat
    5/167 (20 overs)	Heat won by 34 runs
    Scorecard	Perth Scorchers
    9/133 (20 overs)	Perth Scorchers	WACA Ground	Perth	18,517
    2013–14
    Details	Perth Scorchers
    4/191 (20 overs)	Scorchers won by 39 runs
    Scorecard	Hobart Hurricanes
    7/152 (20 overs)	Perth Scorchers	WACA Ground	Perth	20,783
    2014–15
    Details	Perth Scorchers
    6/148 (20 overs)	Scorchers won by 4 wickets
    Scorecard	Sydney Sixers
    5/147 (20 overs)	Neutral venue	Manuka Oval	Canberra	11,837
    2015–16
    Details	Sydney Thunder
    7/181 (19.3 overs)	Thunder won by 3 wickets
    Scorecard	Melbourne Stars
    9/176 (20 overs)	Melbourne Stars	MCG	Melbourne	47,672
    2016–17
    Details	Perth Scorchers
    1/144 (15.5 overs)	Scorchers won by 9 wickets
    Scorecard	Sydney Sixers
    9/141 (20 overs)	Perth Scorchers	WACA Ground	Perth	21,832
    2017–18
    Details	Adelaide Strikers
    2/202 (20 overs)	Strikers won by 25 runs
    Scorecard	Hobart Hurricanes
    5/177 (20 overs)	Adelaide Strikers	Adelaide Oval	Adelaide	40,732
    2018–19
    Details	Melbourne Renegades
    5/145 (20 overs)	Renegades won by 13 runs
    Scorecard	Melbourne Stars
    7/132 (20 overs)	Melbourne Renegades	Docklands Stadium	Melbourne	40,816
    2019–20
    Details	Sydney Sixers
    5/116 (12 overs)	Sixers won by 19 runs
    Scorecard	Melbourne Stars
    6/97 (12 overs)	Sydney Sixers	SCG	Sydney	10,121
    2020–21
    Details	Sydney Sixers
    6/188 (20 overs)	Sixers won by 27 runs
    Scorecard	Perth Scorchers
    9/161 (20 overs)	Sydney Sixers	SCG	Sydney	25,295
    2021–22
    Details	Perth Scorchers
    6/171 (20 overs)	Scorchers won by 79 runs
    Scorecard	Sydney Sixers
    10/92 (16.2 overs)	Neutral venue	Docklands Stadium	Melbourne	10,333
    2022–23
    Details	Perth Scorchers
    5/178 (19.2 overs)	Scorchers won by 5 wickets
    Scorecard	Brisbane Heat
    7/175 (20 overs)	Perth Scorchers	Perth Stadium	Perth	53,886
    </p>
</body>
</html>
ICC.HTML,
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>2023 Cricket World Cup</h1>
    <img src="https://upload.wikimedia.org/wikipedia/en/thumb/e/eb/2023_CWC_Logo.svg/330px-2023_CWC_Logo.svg.png" alt="">
    <p>The 2023 ICC Men's Cricket World Cup was the 13th edition of the Cricket World Cup, a quadrennial One Day International (ODI) cricket tournament contested by men's national teams and organised by the International Cricket Council (ICC). Ten national teams participated in the tournament, which was hosted by India. It started on 5 October and concluded on 19 November 2023, with Australia winning the tournament.[1]

        It was the first men's Cricket World Cup which India hosted solely. The tournament took place in ten different stadiums, in ten cities across the country. In the first semi-final India beat New Zealand, and in the second semi-final Australia beat South Africa. The final took place between India and Australia at Narendra Modi Stadium on 19 November with Australia winning the title for the sixth time.[2]
        
        The top eight placed teams in the tournament's final points table qualified for the 2025 ICC Champions Trophy, the next ICC ODI tournament. Virat Kohli was the player of the tournament and also scored the most runs; Mohammed Shami was the leading wicket-taker. A total of 1,250,307 spectators attended matches, the highest number in any cricket World Cup to date.[3]</p>
    <h2>Qualification</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7d/2023_Cricket_World_Cup_participating_nations.svg/600px-2023_Cricket_World_Cup_participating_nations.svg.png" alt="">
    <p>Other than India, who qualified as hosts, all teams had to qualify for the tournament through the 2023 Cricket World Cup qualification process. Afghanistan, Australia, Bangladesh, England, New Zealand, Pakistan and South Africa qualified via the ICC Cricket World Cup Super League, with the Netherlands and Sri Lanka securing the final two places via the 2023 Cricket World Cup Qualifier in Zimbabwe during June and July 2023.

        As a result of the qualifying process, the competition was the first not to include former winners West Indies, who failed to progress for the first time after their defeat to Scotland.[15] Full members Ireland and Zimbabwe also missed out on qualification, meaning three of the four full members who took part in the knock-out qualification stage did not qualify, with only Sri Lanka progressing.[16] The final qualification spot was decided by an eliminator match between associate members Scotland and the Netherlands,[17] with the Dutch side taking the final place.[15]
        
        Means of qualification	Date	Venue	Berths	Qualified
        Host nation	—	—	1	 India
        ICC Super League	30 July 2020 – 14 May 2023	Various	7	
         Afghanistan
         Australia
         Bangladesh
         England
         New Zealand
         Pakistan
         South Africa
        Qualifier	18 June 2023 – 9 July 2023	Zimbabwe	2	
         Sri Lanka
         Netherlands
        Total	10	</p>
        <h3>Venues</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c2/India_location_map2.svg/450px-India_location_map2.svg.png" alt="">
        <p>The tournament took place in ten different stadiums, situated in ten different cities across India. The first and second semi-finals were held at Wankhede Stadium in Mumbai and Eden Gardens in Kolkata respectively, while the final took place at Narendra Modi Stadium in Ahmedabad.[8]

        The BCCI provided funding for renovations and refurbishments at stadiums. Himachal Pradesh Cricket Association Stadium received a new grass surface, drainage system, seating, and hospitality boxes. Wankhede Stadium had upgrades to the outfield, floodlights, corporate boxes, and toilets. M. A. Chidambaram Stadium installed new floodlights and relaid two wickets.[18]
        
        With the autumn scheduling of this World Cup, the ICC instituted protocols for reducing the impact of moisture—including dew and rain—on pitch conditions, so that they did not give the team batting second an advantage (as had frequently occurred in the 2021 Men's T20 World Cup). These included using a specific wetting agent, and the boundary set at around 70 m (77 yards) at each stadium, with more grass on the pitch to encourage seam bowling over spin bowling.[19]
        
        Location	Stadium	Capacity[20]	No. of matches
        Ahmedabad	Narendra Modi Stadium	132,000	5
        Bangalore	M. Chinnaswamy Stadium	33,800	5
        Chennai	M. A. Chidambaram Stadium	38,200	5
        Delhi	Arun Jaitley Stadium	35,200	5
        Dharamshala	HPCA Stadium	21,200	5
        Hyderabad	Rajiv Gandhi International Cricket Stadium	39,200	3
        Kolkata	Eden Gardens	68,000	5
        Lucknow	BRSABV Ekana Cricket Stadium	50,100	5
        Mumbai	Wankhede Stadium	33,100	5
        Pune	Maharashtra Cricket Association Stadium	42,700	5
        </p>
        <h4>Group stage</h4>
        <img src="https://www.hindustantimes.com/ht-img/img/2023/06/27/550x309/icc_1687848920000_1687848937427.jpg" alt="">
        <p>The ICC announced the World Cup schedule on 27 June 2023 at an event in Mumbai with a countdown of 100 days to the opening match of the World Cup on 5 October. The group stage started with the match between the finalists of the 2019 Cricket World Cup, New Zealand and England, at Narendra Modi Stadium.[8] On 9 August 2023, nine fixtures, including the match between India and Pakistan, were rescheduled by the ICC.[29] The top seven teams in the tournament, excluding Pakistan who qualify automatically as host, qualified for the 2025 ICC Champions Trophy.[30]

            Points table
            Pos	Teamvte	Pld	W	L	T	NR	Pts	NRR	Qualification
            1	 India (H)	9	9	0	0	0	18	2.570	Advanced to the semi-finals and
            qualified for the 2025 ICC Champions Trophy
            2	 South Africa	9	7	2	0	0	14	1.261
            3	 Australia	9	7	2	0	0	14	0.841
            4	 New Zealand	9	5	4	0	0	10	0.743
            5	 Pakistan	9	4	5	0	0	8	−0.199	Qualified for the 2025 ICC Champions Trophy
            6	 Afghanistan	9	4	5	0	0	8	−0.336
            7	 England	9	3	6	0	0	6	−0.572
            8	 Bangladesh	9	2	7	0	0	4	−1.087
            9	 Sri Lanka	9	2	7	0	0	4	−1.419	
            10	 Netherlands	9	2	7	0	0	4	−1.825
            </p>
            <h5>Knockout stage</h5>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQOEKdByIEg9S6fTq761ImAYcpp-XcMO5q8bwRJiNwNT0NAZZE_F2zgxBFaSbOdLg9BCus&usqp=CAU" alt="">
            <p>The host India was the first team to qualify for the semi-finals after their 302-run win against Sri Lanka, their seventh successive win in the World Cup.[32] India secured the top place amongst the semi-finalists after they beat South Africa by 243 runs on 5 November at Eden Gardens in Kolkata.[33]

                South Africa became the second team to qualify for the semi-finals after Pakistan defeated New Zealand on 4 November,[34] with Australia becoming the third team to qualify after defeating Afghanistan on 7 November.[35] New Zealand confirmed their berth as the fourth team after Pakistan lost their final match against England.[36]
                
                Semi-finals			Final	
                                                      
                1	 India	397/4 (50 overs)		
                4	 New Zealand	327 (48.5 overs)	
                SFW1	 India	240 (50 overs)	
                SFW2	 Australia	241/4 (43 overs)	
                2	 South Africa	212 (49.4 overs)	
                3	 Australia	215/7 (47.2 overs)	
                Semi-finals
                15 November 2023
                14:00 (D/N)
                Scorecard
                India 
                397/4 (50 overs)
                v
                 New Zealand
                327 (48.5 overs)
                India won by 70 runs
                Wankhede Stadium, Mumbai
                16 November 2023
                14:00 (D/N)
                Scorecard
                South Africa 
                212 (49.4 overs)
                v
                 Australia
                215/7 (47.2 overs)
                Australia won by 3 wickets
                Eden Gardens, Kolkata
                </p>
                <h6>Final</h6>
                <img src="https://akm-img-a-in.tosshub.com/businesstoday/images/story/202311/ezgif-sixteen_nine_262.jpg?size=948:533" alt="">
                <p>19 November 2023
                    14:00 (D/N)
                    Scorecard
                    India 
                    240 (50 overs)
                    v
                     Australia
                    241/4 (43 overs)
                    Australia won by 6 wickets
                    Narendra Modi Stadium, Ahmedabad</p><title>World Cup Schedule</title>
                    <style>
                      table {
                        width: 100%;
                        border-collapse: collapse;
                      }
                      th, td {
                        border: 1px solid #ddd;
                        padding: 8px;
                        text-align: left;
                      }
                      th {
                        background-color: #f2f2f2;
                      }
                    </style>
                  </head>
                  <body>
                  
                  <h2>World Cup Finals Schedule</h2>
                  
                  <table>
                    <tr>
                      <th>Date</th>
                      <th>Match</th>
                      <th>Venue</th>
                      <th>won</th>
                    </tr>
                    <tr>
                      <td>June 10, 2023</td>
                      <td>Match 1: Team A vs Team B</td>
                      <td>Stadium X</td>
                    </tr>
                    <tr>
                      <td>June 15, 2023</td>
                      <td>Match 2: Team C vs Team D</td>
                      <td>Stadium Y</td>
                    </tr>
                    <!-- Add more rows for other matches -->
                  </table>
                

</body>
</html>
T20.HTML,
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>T20I series</h1>
    <img src="https://st1.techlusive.in/wp-content/uploads/2023/11/India-vs-Australia-T20-series.jpg" alt="">
    <h2>1st T20I</h2>
    <p>23 November 2023
        19:00 (N)
        Scorecard
        Australia 
        208/3 (20 overs)
        v
         India
        209/8 (19.5 overs)
        Josh Inglis 110 (50)
        Prasidh Krishna 1/50 (4 overs)
        Suryakumar Yadav 80 (42)
        Tanveer Sangha 2/47 (4 overs)
        India won by 2 wickets
        Dr. Y. S. Rajashekar Reddy ACA–VDCA Cricket Stadium, Vishakhapatnam
        Umpires: Nitin Menon (Ind) and Rohan Pandit (Ind)
        Player of the match: Suryakumar Yadav (Ind)
        India won the toss and elected to field.
        Suryakumar Yadav captained India for the first time in T20Is.[16]
        Josh Inglis (Aus) scored his first century in T20Is, and the equal fastest by an Australian (off 47 balls).[17]
        This was India's highest successful run chase in T20Is.</p>
    <h3>2nd T20I</h3>
    <p>26 November 2023
        19:00 (N)
        Scorecard
        India 
        235/4 (20 overs)
        v
         Australia
        191/9 (20 overs)
        Ruturaj Gaikwad 58 (43)
        Nathan Ellis 3/45 (4 overs)
        Marcus Stoinis 45 (25)
        Ravi Bishnoi 3/32 (4 overs)
        India won by 44 runs
        Greenfield International Stadium, Thiruvananthapuram
        Umpires: KN Ananthapadmanabhan (Ind) and Jayaraman Madanagopal (Ind)
        Player of the match: Yashasvi Jaiswal (Ind)
        Australia won the toss and elected to field.
        India's score of 235/4 was its fifth-highest in T20Is.</p>
    <h4>3rd T20I</h4>
    <p>28 November 2023
        19:00 (N)
        Scorecard
        India 
        v
         Australia
        Assam Cricket Association Stadium, Guwahati
        Umpires: Rohan Pandit (Ind) and Virender Sharma (Ind)</p>
    <h5>4th T20I</h5>
     <p>1 December 2023
        19:00 (N)
        Scorecard
        India 
        v
         Australia
        Shaheed Veer Narayan Singh International Cricket Stadium, Raipur
        Umpires: KN Ananthapadmanabhan (Ind) and Jayaraman Madanagopal (Ind)</p>
     <h6>5th T20I</h6>
     <p>3 December 2023
        19:00 (N)
        Scorecard
        India 
        v
         Australia
        M. Chinnaswamy Stadium, Bengaluru
        Umpires: KN Ananthapadmanabhan (Ind) and Rohan Pandit (Ind)
        Notes</p>
</body>
</html>
pkl.HTML,
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Pro Kabaddi League 2023-24 Schedule, Live Streaming, Previous Winners: All You Need To Know About PKL's Latest Season</h1>
    <img src="https://imgnew.outlookindia.com/uploadimage/library/16_9/16_9_5/IMAGE_1665974590.webp" alt="">
</body></html></style>

<div class="__related_stories_thumbs">
<!-- __sectionTitle_rhs mb-15 -->
	<h3 class="__sectionTitle_rhs mb-15 title-bold"><span>Related stories</span></h3>
				<div class="zig-zag row mb-15">
				<div class="col-md-9">
					<h3><a href="/sports/pro-kabaddi-league-2023-24-gujarat-giants-name-fazel-atrachali-as-captain-ahead-of-season-10-news-332558?utm_source=related_story">Pro Kabaddi League 2023-24: Gujarat Giants Name Fazel Atrachali As Captain Ahead Of Season 10</a></h3>
					
					
				</div>
				<div class="col-md-3">
					<figure>
						<a href="/sports/pro-kabaddi-league-2023-24-gujarat-giants-name-fazel-atrachali-as-captain-ahead-of-season-10-news-332558?utm_source=related_story_img">
							<img src="https://imgnew.outlookindia.com/uploadimage/library/16_9/16_9_2/IMAGE_1700748816.webp" class="lazy" loading="lazy" style="width: 150px;">
						</a>
					</figure>
				</div>
			</div>
				<div class="zig-zag row mb-15">
				<div class="col-md-9">
					<h3><a href="/sports/new-zealand-pacer-trent-boult-encourages-teammates-daryl-mitchell-and-tim-southee-to-embrace-kabaddi-challenge-news-332147?utm_source=related_story">New Zealand Pacer Trent Boult Encourages Teammates Daryl Mitchell And Tim Southee To Embrace Kabaddi Challenge</a></h3>
					
					
				</div>
				<div class="col-md-3">
					<figure>
						<a href="/sports/new-zealand-pacer-trent-boult-encourages-teammates-daryl-mitchell-and-tim-southee-to-embrace-kabaddi-challenge-news-332147?utm_source=related_story_img">
							<img src="https://imgnew.outlookindia.com/uploadimage/library/16_9/16_9_2/IMAGE_1696421574.webp" class="lazy" loading="lazy" style="width: 150px;">
						</a>
					</figure>
				</div>
			</div>
				<div class="zig-zag row mb-15">
				<div class="col-md-9">
					<h3><a href="/sports/pro-kabaddi-league-dubki-king-pardeep-narwal-thanks-fans-for-the-support-over-past-10-years-news-327041?utm_source=related_story">Pro Kabaddi League: 'Dubki King' Pardeep Narwal Thanks Fans For The Support Over Past 10 Years</a></h3>
					
					
				</div>
				<div class="col-md-3">
					<figure>
						<a href="/sports/pro-kabaddi-league-dubki-king-pardeep-narwal-thanks-fans-for-the-support-over-past-10-years-news-327041?utm_source=related_story_img">
							<img src="https://imgnew.outlookindia.com/uploadimage/library/16_9/16_9_2/IMAGE_1698394683.webp" class="lazy" loading="lazy" style="width: 150px;">
						</a>
					</figure>
				</div>
			</div>
	</div>
    <a href="/national" target="_self" class="subaction">India </a>
															<div class="subsection_wrapper-mini">
																<div class="subsection_wrapper_inner">
																	<ul>
																																			<li><a href="/topic/uttar-pradesh" target="_self">Uttar Pradesh</a></li>
																																				<li><a href="/topic/rajasthan" target="_self">Rajasthan</a></li>
																																				<li><a href="/topic/madhya-pradesh" target="_self">Madhya Pradesh</a></li>
																																				<li><a href="/topic/chhattisgarh" target="_self">Chhattisgarh</a></li>
																																			</ul>
																</div>
															</div>
														</li>
																												
															<li><a href="/international" target="_self">International</a></li>
																												<li class="mini-subsection">
															<a href="/sports" target="_self" class="subaction">Sports </a>
															<div class="subsection_wrapper-mini">
																<div class="subsection_wrapper_inner">
																	<ul>
																																			<li><a href="/sports/icc-world-cup-2023" target="_self">ICC World Cup 2023</a></li>
																																				<li><a href="/topic/cricket" target="_self">Cricket</a></li>
																																				<li><a href="/topic/football" target="_self">Football</a></li>
																																				<li><a href="/topic/hockey" target="_self">Hockey</a></li>
																																				<li><a href="/topic/badminton" target="_self">Badminton</a></li>
																																				<li><a href="/topic/tennis" target="_self">Tennis</a></li>
																																				<li><a href="/topic/table-tennis" target="_self">Table Tennis</a></li>
																																				<li><a href="/topic/boxing" target="_self">Boxing</a></li>
																																				<li><a href="/topic/nba" target="_self">NBA</a></li>
																																				<li><a href="/topic/formula-1" target="_self">Formula One</a></li>
																																				<li><a href="/topic/mma" target="_self">MMA</a></li>
																																			</ul>
																</div>
															</div>
														</li>
																												
															<li><a href="/art-entertainment" target="_self">Entertainment</a></li>
																												
															<li><a href="/photos" target="_self">Photos</a></li>
																												
															<li><a href="/videos" target="_self">Videos</a></li>
																												
															<li><a href="/weekender" target="_self">Weekender</a></li>
																												
															<li><a href="https://www.outlookindia.com/culture-society" target="_self">Culture</a></li>
																											</ul>
												</div>
											</div>

																		<li><a href="/magazine" style="cursor: context-menu;" target="_self">Magazine</a>
											<div class="subsection_wrapper">
												<div class="subsection_wrapper_inner">
													<ul>
																											
															<li><a href="/magazine/archive" target="_self">Archives</a></li>
																											</ul>
												</div>
											</div>
</body>
</html>
new.css,
css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
}

nav {
    background-color: #555;
    padding: 10px;
    text-align: center;
}

nav button {
    background-color: #fff;
    color: #333;
    padding: 5px 10px;
    font-size: 16px;
    cursor: pointer;
}

main {
    padding: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Add more styles as needed for specific elements, such as teams, matches, etc. */


You can include this CSS code in the <style> tag within the HTML document or save it in a separate CSS file and link it to your HTML file using the <link> tag in the <head> section. Remember to customize the styles based on your design preferences.

If you have specific elements you'd like to style or additional requirements, feel free to ask for more guidance!
sports.css,
/* Basic Reset */
body, h1, h2, h3, ul, li, p, table {
    margin: 0;
    padding: 0;
  }
  
  /* Global Styles */
  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
  }
  
  header {
    background-color: #333;
    color: #fff;
    padding: 20px;
  }
  
  header h1 {
    margin: 0;
  }
  
  nav ul {
    list-style: none;
  }
  
  nav ul li {
    display: inline;
    margin-right: 20px;
  }
  
  nav ul li a {
    color: #fff;
    text-decoration: none;
  }
  
  main {
    padding: 20px;
  }
  
  section {
    margin-bottom: 30px;
  }
  
  footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: #fff;
    position: fixed;
    bottom: 0;
    width: 100%;
  }

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website!</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        * {margin: 0; padding: 0; box-sizing: border-box;}
        body {
            font-family: "Consolas", "Poppins","Cascadia Mono", sans-serif;
            background-color: #000;
            color: limegreen;
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem 1rem;
        }
        h1 {
            text-align: center;
            font-family: "Poppins", "Cascadia Mono", sans-serif;
            margin-bottom: 2rem;
            font-size: 2.5rem;
        }
        h2 {
            color: lightgreen;
            margin: 2rem 0 1rem;
            font-size: 1.8rem;
        }
        a {
            background-color:skyblue;
            color:darkgreen;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.2rem;
            padding:2px;
            display: inline-block;
            margin: 1rem 0;
            transition:all 0.4s ease;
        }
        a:hover {transform:scale(1.2);}
        a:active {transform:scale(1.2);}
        .project-desc {margin: 0.5rem 0; color: #45c9f9;}
        .warning {color: #ff5100; font-weight: 600; margin: 0.5rem 0;}
        img
      {
            max-width: 100%;
            height:auto; 
            border:1px solid limegreen;
            margin:1rem 0;
        }
        .tab-link
        {
            font-family:"Poppins","Cascadia Mono",sans-serif;
            padding:10px 20px;
            background-color:ivory;
            text-decoration:none;
            color:black;
        }
        .tab-content
        {
            display:none;
        }
        .tab-content:target
        {
            display:block;
        }
    </style>
</head>
<body>
    <h1>ruililcu.github.io</h1>
    <h2>Choose a Language!选择语言!</h2>
    <a href="https://ruililcu.github.io/#p12">English</a>
    <a href="https://ruililcu.github.io/#p13">中文</a>
    <br><br>
    <div id="p12" class="tab-content">
        <h2>Ruiililcu's website(Games,Tools)</h2>
        <h2>Collapscension: An incremental game!</h2>
        <p class="project-desc">A JS incremental idle game with break_eternity.js(from Patashu)</p>
        <a href="https://ruililcu.github.io/Collapscension/" target="_blank">Play Now</a>
        <p>Screenshot (responsive preview)</p>
        <img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/c7b3c9cd-cb97-4475-8fcd-94eca9ff9964" />
        <h2>Stock Simu</h2>
        <p class="warning">Only a simulation! Be cautious when investing in real stocks!</p>
        <p class="project-desc">A simple stock trading simulator</p>
        <a href="https://ruililcu.github.io/stock.html" target="_blank">Play Now</a>
        <p>Screenshot</p>
        <img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/c4037a7c-c0f4-41de-b743-ef83cc4b3adc" />
        <h2>RUILILCU'S INFINITY HOTEL</h2>
        <p class="project-desc">An infinite hotel,all the floors are unique</p>
        <a href="https://ruililcu.github.io/hot.html" target="_blank">Play Now</a>
        <p>Screenshot</p>
        <img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/5054a747-ad86-4231-8c91-ab61945b76a0" />
    </div>
        <div id="p13" class="tab-content">
        # 这里也有中文
        <a href="https://ruililcu.github.io/cn.html">切换到中文(旧)</a>
        <h2>我的个人网站(游戏+工具)</h2>
        <h2>坍缩飞升:一个增量游戏!</h2>
        <p class="project-desc">目前是Beta,没有中文</p>
        <img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/c7b3c9cd-cb97-4475-8fcd-94eca9ff9964" />
        <a href="https://ruililcu.github.io/Collapscension/" target="_blank">游玩</a>
        <h2>ruililcu的股票模拟</h2>
        <p class="warning">实盘炒股有风险,实盘投资需谨慎</p>
        <p class="project-desc">一个简单的股票模拟</p>
        <a href="https://ruililcu.github.io/cnprog/stock.html" target="_blank">游玩</a>
            <img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/06dbd022-9122-45b9-bcdd-b9f4b4c81cc8" />
        <h2>ruililcu的酒店</h2>
        <p class="project-desc">所有楼层均为独特!</p>
            <img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/03e28310-76e6-4728-ad66-a03b636775a0" />
        <a href="https://ruililcu.github.io/cnprog/hot.html" target="_blank">游玩</a>
    </div>
</body>
</html>

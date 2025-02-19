# Jinhui Li
### Favorite Words
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=&weight=700&size=13&multiline=true&width=435&lines=%E8%8E%AB%E5%90%AC%E7%A9%BF%E6%9E%97%E6%89%93%E5%8F%B6%E5%A3%B0%2C%E4%BD%95%E5%A6%A8%E5%90%9F%E5%95%B8%E4%B8%94%E5%BE%90%E8%A1%8C%E3%80%82;Ignore+the+noises+around+you%2C+keep+walking+confidently.)]([https://git.io/typing-svg](https://jinhuili-lab.github.io))

    <style>


        body{
            font-variant-caps: all-petite-caps;


        }

        .widget {
            padding: 5px 5px ;
            color: #000000;
            display: flex;
            justify-content:center;
            align-items:center;
            flex-direction: column;
            max-width: 95%;
            margin: auto;
            border: 3px solid #000000;
            border-radius: 5px;
            box-shadow: 2px 2px 1px 0px #000000;

        }

           
        .greet{
            font-size: 3em;
        }

        .date {
      
            font-family: monospace;
            font-size: 2em;
        }

        .clock {
            font-family: monospace;
            font-size: 2em;
        }

        .time {
            display: inline-block;
            min-width: 20px;
        }

        .colon {
            font-size: 1em;
            display: inline-block;
        }

     




    </style>
</head>
<body>




<div class="container>">
    <div class="widget">

            <div class="greet" id="greet"></div>

                <div class="date" id="date"></div>
                <div class="clock">
                    <div class="time" id="hour"></div>
                    <div class="colon">:</div>
                    <div class="time" id="min"></div>
                    <div class="colon">:</div>
                    <div class="time" id="sec"></div>
                </div>
           

        

    </div>
</div>
        



<script>

function dispalyGreetings(today){
        hrs = today.getHours();
        name=""
        if (hrs < 12)
            greet = 'Good Morning  '+name;
        else if (hrs >= 12 && hrs <= 17)
            greet = 'Good Afternoon '+name;
        else if (hrs >= 17 && hrs <= 24)
            greet = 'Good Evening  '+name;
        document.getElementById('greet').innerHTML = greet;

    }

    function dispalyDate(today) {  
       
        const days = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'];
        const monthNames = ["January", "February", "March", "April", "May", "June",
  "July", "August", "September", "October", "November", "December"
];

        var dayName = days[today.getDay()];
        var monthName = monthNames[today.getMonth()];
        var date = today.getDate();
        var year = today.getFullYear();
        document.getElementById('date').innerHTML =dayName+", "+monthName+" "+date+" "+year;

    }


    function dispalyClock(today) {

        var hour = padZeros(twelveHour(today.getHours()));
        var minutes = padZeros(today.getMinutes());
        var seconds = padZeros(today.getSeconds());
       
        if(today.getHours() >=12){
            seconds+=" pm"
        }
        else{
            seconds+=" am"
        }
       
        document.getElementById('hour').innerHTML = hour;
        document.getElementById('min').innerHTML = minutes;
        document.getElementById('sec').innerHTML = seconds;
    }

    function twelveHour(hour) {
        if (hour > 12) {
            return hour -= 12
        } else if (hour === 0) {
            return hour = 12;
        } else {
            return hour
        }
    }
    function padZeros(num) {
        if (num < 10) {
            num = '0' + num
        };
        return num;
    }

    function dispalyWidget() {
        var today = new Date();
        dispalyGreetings(today);
        dispalyDate(today);
        dispalyClock(today);
        setTimeout(dispalyWidget, 500);
    }

    dispalyWidget()

</script>

</body>
</html>
### Hi there 
- 🔭 This is  **Jinhui Li**.  
- ✨ ~~I am an algorithm researcher in the R&D center of BGI group.~~- Now I am a Ph.D student in America. 
- ⚡ I focus on **Bioinformatics algorithm** and **Biostatistics method**.
- 👋 I enjoy coding.
- 💬 Less is more, do the interesting things.
- ☛ [Google Scolar](https://scholar.google.com/citations?user=T4z1JAQAAAAJ&hl) | [Home pages](https://jinhuili-lab.github.io/) | [Resume](https://jinhuili-lab.github.io/resume/index_en.html) | [INS](https://www.instagram.com/jinhui_li_1997/) | [Linkin](https://www.linkedin.com/in/jinhui-li-063961126/) | [Blog](https://jinhuili-lab.github.io/blog/)
  
### Experience
- 🤔 When I got my bachelor's degree, I was interested in computer science. 😄 So I joined a biomedical company as a bioinformatics engineer and focused on the bioinformatics analysis for NGS data. The company developed many products for PGS(3rd-generation IVF), such as a reagent test kit for detecting the variance of Genomics and developing the bioinformatics cloud platform.
- 👯 During the part of my master's degree, metagenomics attracted my attention. It is my first time to use AI techniques and publish a paper as a first author. In this stage, I published two papers as the first author and got the National Scholarship of China. 
- ☛ After that, I worked for the BGI group as a bioinformatics algorithms  researcher and developed some non-open source software for the MGI sequencers, such as PFI, MGI. Relying on the Ztron system and PFI kit, users can get the website report of cancer genomics analyzed after inputting the biology sample into the MGI sequencer. 
- ☎ Now I am pursuing a Ph.D. degree in America. If you have any questions about multi-omics analysis, software development, and database development, don't hesitate to get in touch with me by email: ijinhui@outlook.com, jinhui.li@slu.edu or ijinhui@foxmail.com.
<center>

 
 <img align="center" src="https://github.com/jinhuili-lab/jinhuili-lab/blob/main/github-contribution-grid-snake.svg"/>
 
 |<img align="center" src="https://github-readme-stats.vercel.app/api?username=jinhuili-lab&show_icons=true&theme=buefy&hide_border=true" alt="Calcium-Ion's github stats" /> |<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jinhuili-lab&layout=compact&theme=buefy&hide_border=true&hide=html,css" /> |
| ------------- | ------------- |

|Technique|Python|PHP|R|HTML|Javascript|CSS|Gradio|Plotly|
|---|---|---|---|---|---|---|---|---|
|Proficiency|★★★★|★★★★|★★★★|★★★|★★|★★|★★|★★★|

|Skill|Machine Learning|Deep learning|Genomics|Bioinformatics|Server maintain|
|---|---|---|---|---|---|
|Proficiency|★★★★|★★★★|★★★★|★★★★★|★★★★|

</center>

### Previous Work 

#### Microbiosee2
- [MicrobioSee2 ](https://github.com/jinhuili-lab/MicrobioSee2/releases/tag/v2.0.2)
- [Source code](https://github.com/jinhuili-lab/MicrobioSee2/)
- [User Guide](https://microbiosee.github.io/)
* ![](https://github.com/jinhuili-lab/jinhuili-lab/blob/main/pic01.jpg)   
#### SMDB
- [SMDB website](https://smdb.gxu.edu.cn/)
* ![](https://github.com/jinhuili-lab/jinhuili-lab/blob/main/map00920.png)

### Life
- INSTAGRAM
  <a href="https://www.instagram.com/jinhui_james_li/"><img src="https://raw.githubusercontent.com/jinhuili-lab/personal_image_bed/master/img9920240511210920.png" /></a>
- BLOG
  <a href="https://jinhuili-lab.github.io/blog/">Jinhui Zone</a>

  

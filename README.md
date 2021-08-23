- 👋 Hi, I’m @MrKacyk
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
MrKacyk/MrKacyk is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


<!DOCTYPE html> 
<html lang="pl">
<html>
<head>
    <meta charset="utf-8"/>
    <meta name="description" content="CV Patryka Kacperek-Poczatkujacy Programista frontowy"/>
    <meta name="keywords" content="szukam pracownika, pracownik Html, pracownik CSS, pracownik C++"/>
    <meta name="author" content="Patryk Kacperek" />
    <link rel="stylesheet" href="style.css">
    <title>CV_Patryk_Kacperek</title>


</head>
<body>
    <div id="stronaCv">
        <header>
            <div id="dane">
                <h1>Patryk Kacperek</h1>
                <div style="clear: both;"></div>
                <div class="opis1">

                    <ul id="op1">
                        <li>E-mail:</li>
                        <li>Telefon:</li>
                        <li>Data Urodzenia:</li>
                        <li>Miejscowość:</li>
                    </ul>

                </div>    
                <div class="opis1">    
                    
                    <ul id="op1">
                        <li><a href="mailto:patrolos994@gmail.com">patrolos994@gmail.com</a></li>
                        <li><a href="tel:+48730249416">730249416<a></li>
                        <li>28.01.1994r</li>
                        <li>Zabrze</li>
                    </ul>

                </div>   
                <img id="img" src="img 228x250.jpg" alt="Patryk Kacperek">
                <div style="clear: both;"></div>
                
            </div>
                <div class="opis2">

                    <h2>Wykształcenie</h2>

                            <h3>Centrum kształcenia ustawicznego nr1</h3>
                            <div>09/2014-06/2015</div>
                            
                                <ul>
                                    <li>Górnictwo i Geologia</li>
                                    <li>Górnik</li>
                                    <li>Zawodowe</li>
                                </ul>
                            </div>    
                            
                </div>

            <section>  
                <div class="opis2">

                        <h2>Umiejętności</h2>
                        <ul>
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>C++</li>
                            <li>JavaScript</li>                
                        </ul>

                </div>
            </section>      
        </header>    
    </div>

</body>
</html>
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

body
{
    margin: 0px;
    background-color: rgb(95, 84, 84);
    
}
#stronaCv
{
    width: 600px;
    padding: 15px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    background-color: white;
    
}
#dane
{
    background-color: rgb(255, 255, 255);
    height: 300px;
    margin-left: auto;
    margin-right: auto;
    margin-top: 25px;
    border-top: groove 3px black;
    border-bottom: groove 3px black;
    padding-left: 15px;
    padding-right: 10px;
    padding-top: 10px;
    padding-bottom: 3px;
}
h1
{
    font-style: italic;
}
#img
{
    float: right;
    position: relative;
    bottom: 65px;
    
    
}
.opis1
{
    width: 150px;
    display: inline-block;
}
#op1
{
    list-style-type: none;
    padding: 0px;
    display: inline-block;
    margin:0;

}
.opis2
{
    margin-bottom: 30px;
    margin-left: auto;
    margin-right: auto;
    padding-right: 5px;
    padding-left: 5px;
    padding-top: 10px;
    padding-bottom: 10px;
    border-bottom: solid 2px #000;
}
h3
{
    margin: 0px;
}








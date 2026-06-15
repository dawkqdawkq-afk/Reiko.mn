# Reiko.mn
Welcome to Reiko
<!DOCTYPE html>
<html lang="mn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Reiko.mn</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    overflow:hidden;
    background:black;
    font-family:Arial, sans-serif;
}

#welcome{
    position:fixed;
    width:100%;
    height:100%;
    display:flex;
    justify-content:center;
    align-items:center;
    background:black;
    color:white;
    font-size:40px;
    font-weight:bold;
}

#main{
    display:none;
    width:100vw;
    height:100vh;
}

#main img{
    width:100%;
    height:100%;
    object-fit:cover;
}
</style>
</head>

<body>

<div id="welcome">
    Reiko.mn-д тавтай морил
</div>

<div id="main">
    <img src="background.jpg" alt="Reiko">
</div>

<script>
setTimeout(() => {
    document.getElementById("welcome").style.display = "none";
    document.getElementById("main").style.display = "block";
}, 3000);
</script>

</body>
</html>

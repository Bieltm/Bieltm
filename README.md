<!DOCTYPE html>
<html lang="ca">
<head>
    <meta charset="UTF-8">
    <title>Portfolio - Biel Torruella</title>
    <style>
        /* Aquest és el "truc" per posar-ho en fila */
        .skills {
            display: flex;       /* Activa el mode flexible */
            flex-direction: row; /* Força la fila */
            flex-wrap: wrap;     /* Si no caben, baixen a la següent línia */
            gap: 20px;           /* Espai entre logos */
            align-items: center; /* Alineació vertical */
            margin-top: 20px;
        }

        .skills img {
            object-fit: contain; /* Evita que les imatges es deformin */
        }
    </style>
</head>
<body>

    <h1>Hey! I'm Biel Torruella</h1>
    
    <p>My passion for technology and mathematics has been a constant throughout my life. Driven by curiosity, I started programming as a self-taught developer creating video games with Game Maker Studio—an experience that solidified my decision to pursue a degree in Computer Engineering. Currently, I am steering my career towards Artificial Intelligence and Data Science. I find that these fields offer the perfect blend of technical challenges and mathematical foundations, driving my motivation to continuously learn and innovate.</p>

    <h2>My Skillset:</h2>

    <div class="skills">
        <img src='https://blog.desafiolatam.com/wp-content/uploads/2018/05/java-logo.png' alt="Java" width="100" height="100">
        <img src='https://upload.wikimedia.org/wikipedia/commons/1/19/C_Logo.png' alt="C" width="70" height="100">
        <img src='https://cdn.pixabay.com/photo/2024/03/31/02/11/python-8665904_1280.png' alt="Python" width="100" height="100">
        <img src='https://cdn.pixabay.com/photo/2017/01/31/15/33/linux-2025130_1280.png' alt="Linux" width="100" height="100">
        <img src='https://icones.pro/wp-content/uploads/2021/05/icone-html-orange.png' alt="HTML" width="100" height="100">
        <img src='https://raw.githubusercontent.com/github/explore/6c6508f34230f0ac0d49e847a326429eefbfc030/topics/css/css.png' alt="CSS" width="100" height="100">
        <img src='https://img.icons8.com/?size=512&id=108784&format=png' alt="JS" width="100" height="100">
        <img src='https://images.seeklogo.com/logo-png/43/2/azure-sql-logo-png_seeklogo-434048.png' alt="SQL" width="100" height="100">
    </div>

</body>
</html>

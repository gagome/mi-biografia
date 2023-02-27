.bodi{
            font-family: sans-serif;
            margin: 0;
            box-sizing: border-box;
        }
        .a{
            text-decoration: none;
            color: black ;
        }
        .encabezado{
            display: flex;
            min-height: 7px;
            justify-content: space-between;
            align-items: center;
            background-color: aqua;
            padding: 0%;
            margin-bottom: 0;
        }
        .logo{
            display: flex;
            align-items: center;
            text-decoration: none;
            color: black;
            padding-left: 50px;
            padding-right: 50px;
        }
        .logo img{
            height: 100px;
            margin-right: 10px;
            margin-left: 15px;
        }
        .NamePage{
            font-family: 'Indie Flower', cursive;
        }
        .vinculos{
            font-weight: 600;
            text-decoration: none;
            color: black;
            margin-right: 10px;  
            font-size: 150%;
            font-family: 'Righteous', cursive;
        }
        .nav{
            padding-right: 50px;
            padding-left: 50px;
        }
        nav a:hover{
            color: white;
            font-size: 200%;
        }
        nav a:active{
            font-size: 150%;
            color: black;
        }
        .NombrePagina{
            font-family: 'Sassy Frass', cursive;
            font-size: 300%
        }
        .seccion1{
            background-color: coral;
            margin-top: 0;
            min-height: 50px;
        }
        .thola{
            font-family: 'Pacifico', cursive;
            padding-right: 520px ;
        }
        .seccion2{
            background-color: coral;
            display: flex;
            height: 384px;
        }
        .fotoyo{
            margin-right: 300px;
            margin-left: 200px;
            height: 300px;
            padding-bottom: 20px;
        }
        .parrafo{
            margin-left: 300px;
            font-size: 150%;
            font-family: 'Satisfy', cursive;
            padding-top: 15px;
        }
        @media (max-width:869px){
             .encabezado{
                flex-direction: column;
             }
             .vinculos{
                padding-bottom: 10px;
             }
        }
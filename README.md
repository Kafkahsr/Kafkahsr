    <link href="https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400..800;1,400..800&display=swap" rel="stylesheet">
    <style>
        
        body {
            
            font-family: 'EB Garamond', serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
        }

        
        .button-container {
            text-align: center;
        }

        
        .button {
            font-family: 'EB Garamond', serif;
            font-size: 1.2rem; 
            font-weight: 500;  
            color: black;       
            background-color: transparent; 
            text-decoration: none; 
            display: inline-block;
            padding: 8px 0;    
            margin: 0 15px;   
            position: relative;
            transition: color 0.3s ease;
          
        }

        
        .button::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;        
            height: 2px;       
            background-color: black; 
            transform: scaleX(1); 
            transition: transform 0.2s ease;
        }

      

      
        .button:hover {
            color: #333;
        }

        /* Можна додати ефект для кліку */
        .button:active {
            transform: translateY(1px);
        }
    </style>
</head>
<body>
    <div class="button-container">
        <a href="" class="button">Rus</a>
        <a href="" class="button">Usa</a>
        <a href="" class="button">Uk</a>
    </div>

<img src="https://i.pinimg.com/1200x/22/72/94/22729421a04c7afca17affc00aa692fe.jpg" style="width:100%; height:40px; display: block;">

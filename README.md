<html>
    <head>
        <meta charset="utf-8">
        <title>HTML: Lists</title>
<style>
        
          p {
            color:rgb(176, 37, 176);
        }
    
        h1 {
            color: rgb(240, 201, 240);
            font-size: 1.5em;
             }
        
         body { 
             background-color: rgb(163, 196, 114);
             font-size: 12px;
         }
            #rabbits-song {
            background-color: yellow;
        }
        
        #rabbits-info-heading { lo reemplazo por .song-lyrics
            background-color: purple;
        }

        p{
            color:rgb(191, 0, 255);
            font-family: "Helvetica", sans-serif;
        } 
    


        .song-lyrics:{

          backgound-color:yellow;
          font-family: monospace;
          font-size: 13px;
          font-style: italic;
          font-weigth:120;
          line-height: 1.5em;
            text-align: center;
        }
    
        
        a {
            text-decoration: none;
        }
        }

        </style>

    </head>
    <body>

    <h1>All about rabbits!</h1>

<img src="https://www.kasandbox.org/programming-images/animals/rabbit.png" alt="Rabbit with lop ears in barn" width="203"> 
    
    <h2 id="rabbits-info-heading">Basic info</h2>
    
    <ul>
        <li>They're furry!</li>
        <li>Great listeners!</li>
        <li>Eat all your leftover carrots!</li>
    </ul>
    
    <h3>Top 3 most famous rabbits</h3>
    
    <ol>
        <li>Bugs bunny</li>
        <li>Easter Bunny</li>
        <li>Thumper</li>
    </ol>
    
    <h2>Basic info</h2>
    
    <p class="song-lyrics">Rabbits are little creatures with long ears and puffy tails, 
    and they move their nose up and down in an adorable way
    They eat the most orange vegetables in <em>our</em> world, and <strong>they reproduce more than any human <em>ever</em> has</strong>.</p>
    
    <h2>Songs</h2>
    
    <p id="rabbits-song">Little Bunny Foo Foo, <br>
I don't want to see you <br>
scooping up the field mice <br>
and bopping them on the head!</p>

    </body>
</html

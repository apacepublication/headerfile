# headerfile

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Creating Fixed Header and Footer with CSS</title>
<style>
    /* Add some padding on document's body to prevent the content
    to go underneath the header and footer */
    body{        
        padding-top: 60px;
        padding-bottom: 40px;
    }
    .container{
        width: 80%;
        margin: 0 auto; /* Center the DIV horizontally */
    }
    .fixed-header, .fixed-footer{
        width: 100%;
        position: fixed;        
        background: #333;
        padding: 10px 0;
        color: #fff;
    }
    .fixed-header{
        top: 0;
    }
    .fixed-footer{
        bottom: 0;
    }    
    /* Some more styles to beutify this example */
    nav a{
        color: #fff;
        text-decoration: none;
        padding: 7px 25px;
        display: inline-block;
    }
    .container p{
        line-height: 400px; /* Create scrollbar to test positioning */
    }
</style>
</head>
<body>
    <div class="fixed-header">
        <div class="container">
            <nav>
                <a href="#">Home</a>
                <a href="#">About</a>
                <a href="#">Our Mazagine</a>
                <a href="#">Author</a>
                <a href="#">Media</a>
                <a href="#">Blogger</a>
                <a href="#">Services</a>
                <a href="#">Contact Us</a>
            </nav>
        </div>
    </div>
    <div class="container">
    	<p>good peoples are always supporting yours</p>
        <p>shivangi is a good girl</p>
    </div>    
    <div class="fixed-footer">
        <div class="container">Copyright &copy; Apace Publication</div>        
    </div>
</body>
</html>

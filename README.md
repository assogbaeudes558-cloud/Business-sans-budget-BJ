*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
}

body{
background:#f5f7fa;
color:#222;
line-height:1.6;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:#0d6efd;
color:white;
position:sticky;
top:0;
}

.logo span{
color:#00d26a;
}

nav a{
text-decoration:none;
color:white;
margin:0 15px;
font-weight:600;
}

nav a:hover{
color:#00d26a;
}

.btn{
background:#25D366;
color:white;
padding:12px 22px;
border-radius:8px;
text-decoration:none;
font-weight:bold;
}

.hero{
display:flex;
justify-content:space-between;
align-items:center;
padding:80px 8%;
}

.hero-text{
width:50%;
}

.hero-text h1{
font-size:55px;
margin-bottom:20px;
}

.hero-text span{
color:#0d6efd;
}

.hero-text p{
font-size:18px;
margin-bottom:30px;
}

.btn2{
display:inline-block;
background:#0d6efd;
color:white;
padding:15px 25px;
border-radius:8px;
text-decoration:none;
}

.hero-image img{
width:500px;
max-width:100%;
}

section{
padding:70px 8%;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
margin-top:40px;
}

.card{
background:white;
padding:30px;
border-radius:15px;
text-align:center;
box-shadow:0 5px 20px rgba(0,0,0,.1);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card i{
font-size:45px;
color:#0d6efd;
margin-bottom:15px;
}

#contact{
text-align:center;
background:#0d6efd;
color:white;
}

footer{
padding:30px;
text-align:center;
background:#111;
color:white;
}

@media(max-width:900px){

header{
flex-direction:column;
}

nav{
margin:20px 0;
}

.hero{
flex-direction:column;
text-align:center;
}

.hero-text{
width:100%;
}

.hero-image{
margin-top:40px;
}

.hero-text h1{
font-size:40px;
}

}

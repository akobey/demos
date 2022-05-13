#demo{
position: relative;
padding: 5rem 0;
}
.card{
width: 500px;
height: 500px;
position: relative;
}
.card-body .card-img{
width: inherit;
height: inherit;
transition: all 0.5s ease;
transform-origin: bottom;

}
.card-body{
position: absolute;
top: 0;
left: 0;
z-index: 1;
}
.card-body-back{
background-color: rgba(0,0,0, 0.6);
position: absolute;
width: inherit;
height: inherit;
}

.card-body-back ul{
display: flex;
}
.card-body-back ul{
gap: 2rem;
}
.card-body-back ul li a{
color: white;
display: flex;
align-items: center;
justify-content: center;
width: 3rem;
height: 3rem;
border: 2px solid white;
//border-radius: 50%;
transition: all 0.5s ease;
}
.card-body-back ul li a:hover{
background-color: #eee;
color: #3dd5f3;
}

.centerFlex{
display: flex;
align-items: center;
justify-content: center;
}
//.card-body-back{
//z-index: 1;
//}

//.card-body .card-img img:hover .card-body-back{
//  z-index: 1;
//}
//.card-body:hover .card-img {
//  transform: translateY(-100%) rotateX(90deg);
//}
//.card-body:hover .card-body-back {
//  transform: translateY(0) rotateX(0);
//}
.card-body:hover .card-img {
transform: translateY(-100%) rotateX(90deg);
}
.card-body:hover .card-body-back{
z-index: 1;
}
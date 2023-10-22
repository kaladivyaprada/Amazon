import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';

function Shopping(){
    return(
        <div className='cart'>
            
            <div class="div">
        <nav>
            <ul>
            <marquee scrollamount="10" direction="right" hspace="10px"  behavior="alternate"> <b><li id='aaa'>My Amazon Shopping</li></b></marquee>
                <a href="#"><li>All</li></a>
                <a href="#"><li>AmazonMiniTV</li></a>
                <a href="#"><li>Best Sellers</li></a>
                <a href="#"><li>Today's Deals</li></a>
                <a href="#"><li>Customer Service</li></a>
                <a href="#"><li>Prime</li></a>
                <a href="#"><li>Fashion</li></a>
                <a href="#"><li>Customer Service</li></a>
                <a href="#"><li>New Releases</li></a>
                <a href="#"><li id='cart'>My Cart</li></a>
            </ul>
        </nav>
        </div>  
        <div className='shop'>
            <div id='ing'></div>

            <div id='show'></div>
            
            </div>  
            

          <div class='head'>
            <div id='god'>
                
            <a href="#"><p>Deals</p></a><img  src='https://www.cardexpert.in/wp-content/uploads/2022/08/Weekly-offers.gif' alt='image1' height='100px' width='170px'></img>
       
           <a href="#"><p>Mobiles</p></a><img src='https://m.economictimes.com/thumb/height-450,width-600,imgsize-46138,msid-97738475/best-iphone-models.jpg' alt='image1' height='100px'></img>
                
            <a href="#"><p>Fashion</p></a><img src='https://e0.pxfuel.com/wallpapers/304/361/desktop-wallpaper-womens-fashion-girls-fashion-dress-red-fashion-beauty-dress.jpg' alt='image1' height='100px'></img>
                
            <a href="#"><p>Footwear</p></a><img src='https://cdn.pixabay.com/photo/2020/05/03/19/09/nike-5126389_640.jpg' alt='image1' height='100px'></img>
                
            <a href="#"><p>Home</p></a><img src='https://us.123rf.com/450wm/fabrikacrimea/fabrikacrimea2111/fabrikacrimea211101602/176811383-set-of-stainless-steel-saucepans-in-a-kitchen.jpg?ver=6' alt='image1' height='100px'></img>
                
            <a href="#"><p>Beauty</p></a><img src='https://media.istockphoto.com/id/517742444/photo/makeup-brushes-workplace-makeup-artist.webp?b=1&s=170667a&w=0&k=20&c=qnJtttG_ukDc36YCrZmtxtgiYgEL34LsBgwG1qlD3CE=' alt='image1' height='100px'></img>

            
             
                   </div>    
        </div>
</div>
    )
};

export default Shopping;
<template>
    <div class="background-image">
        <div class="navbar">
            <navBar />
        </div>
        <div class="container">
            <div class="first-section">
                <h4>Discover</h4>
                <h5>Haus Catering</h5>

                <p>OPENING HOURS</p>
                <p>Monday - FridaY 08:00 HRS - 23:00 HRS</p>
                <p>WEEKENDS 08:00 HRS - 23:00 HRS</p>
            </div>
        </div>
    </div>


    <div class="second-section">
        <div class="row">
            <div class="col-md-4 col-sm-12 d-flex justify-content-center align-items-center">
                <img src="/Assets/spices.png" alt="">
            </div>
            <div class="col-md-4 col-sm-12 d-flex justify-content-center align-items-center">
                <div class="row">
                    <div class="col text-center">
                        <h4>Our Story</h4>
                        <h3>LOVE FOR FOOD</h3>
                        <hr>
                        <p>Welcome. This is Royal plate. Elegant & sophisticated restaurant template. Royal plate offers
                            different home page layouts with smart and unique design, showcasing beautifully designed
                            elements every restaurant website should have. Smooth animations, fast loading and engaging user
                            experience are just some of the features this template offers.
                            So, give it a try and dive into a world of royal restaurant websites.</p>
                    </div>
                </div>


            </div>
            <div class="col-md-4 col-sm-12 d-flex justify-content-center align-items-center">
                <img src="/Assets/spices.png" alt="">
            </div>
        </div>
    </div>


    <div class="third-section d-flex justify-content-center align-items-center">
        <div class="text-center">
            <h4>Exquisite cuisine</h4>
            <h3>A FEAST FOR YOUR SENSES</h3>
        </div>
    </div>


    <div class="fourth-section">
        <div class="row">
            <div class="col">
                <div class="row">
                    <div class="col">
                        <img src="/Assets/food1.jpg" alt="" class="square-img">
                    </div>
                    <div class="col">
                        <img src="/Assets/food2.jpg" alt="" class="square-img">
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        <img src="/Assets/food2.jpg" alt="" class="square-img">
                    </div>
                    <div class="col">
                        <img src="/Assets/food4.jpg" alt="" class="square-img">
                    </div>
                </div>
            </div>
            <div class="col">
                <h4>From the menu</h4>
                <h3>Special Offers</h3>
                <hr>
                <div class="row">
                    <div class="col">
                        <img src="/Assets/breakfast.jpg" alt="" class="circular-image">
                    </div>
                    <div class="col">
                        <h6>ROYAL BREAKFAST</h6>
                        <p>Fried eggs, fried bacon, toast, fresh tomato salad, cup of coffee or tea</p>
                    </div>
                </div>

                <div class="row">
                    <div class="col">
                        <img src="/Assets/lunch.jpg" alt="" class="circular-image">
                    </div>
                    <div class="col">
                        <h6>ROYAL BRUNCH</h6>
                        <p>Warm chicken wings, portobello mushrooms, fresh mozzarella, coffe or tea</p>
                    </div>
                </div>

                <div class="row">
                    <div class="col ">
                        <img src="/Assets/dinner.jpg" alt="" class="circular-image">
                    </div>
                    <div class="col ">
                        <h6>ROYAL DINNER</h6>
                        <p>Grilled Beaf steak, roasted red potatos with rosemary, mashrooms sause, vine</p>
                    </div>
                </div>

            </div>
        </div>
    </div>

    <div class="fifth-section">
        <div class="row">
            <div class="col-md-4 col-sm-12 d-flex justify-content-center align-items-center">
                <img src="/Assets/spices.png" alt="">
            </div>
            <div class="col-md-4 col-sm-12 d-flex justify-content-center align-items-center">
                <div class="row">
                    <div class="col text-center">
                        <h4>Reservation</h4>
                        <h3>BOOK US TODAY</h3>
                        <hr>

                        <form>

                            <div class="form-group">
                                <label for="exampleInputPassword1">Name</label>
                                <input type="text" class="form-control" id="exampleInputPassword1"
                                    placeholder="text">
                            </div>
                            <div class="form-group">
                                <label for="exampleInputEmail1">Email address</label>
                                <input type="email" class="form-control" id="exampleInputEmail1"
                                    aria-describedby="emailHelp" placeholder="Enter email">
                               
                            </div>
                            <div class="form-group">
                                <label for="exampleInputPassword1">PhoneNumber</label>
                                <input type="number" class="form-control" id="exampleInputPassword1"
                                    placeholder="number">
                            </div>
                            <div class="form-group">
                                <label for="exampleInputPassword1">Date</label>
                                <input type="date" class="form-control" id="exampleInputPassword1"
                                    placeholder="date">
                            </div>
                            <div class="form-group">
                                <label for="exampleInputPassword1">Expected Guests</label>
                                <input type="number" class="form-control" id="exampleInputPassword1"
                                    placeholder="number">
                            </div>
                            
                            <button type="submit" class="btn btn-success mt-3 mb-5">GET QUOTE</button>
                        </form>

                    </div>
                </div>


            </div>
            <div class="col-md-4 col-sm-12 d-flex justify-content-center align-items-center">
                <img src="/Assets/spices.png" alt="">
            </div>
        </div>
    </div>

    <div class="footer">
        <footerPage />
    </div>
</template>
  
<style scoped>
* {
    overflow-x: hidden;
}

.background-image {
    background-image: url('https://img.freepik.com/free-photo/top-view-pan-with-fish-copy-space_23-2148643622.jpg?size=626&ext=jpg&uid=R70526158&ga=GA1.1.760600717.1689251505&semt=ais');
    background-size: cover;
    /* Make the background image cover the entire section */
    background-repeat: no-repeat;
    /* Prevent the image from repeating */
    background-position: center center;
    /* Center the image within the section */
}

.first-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    /* Center the items horizontally */
    justify-content: center;
    /* Center the items vertically */
    height: 100vh;
    color: #fff;
    /* Change the text color to white to improve visibility */
}

.second-section {
    height: 70vh;
}

.third-section {
    background-image: url('https://img.freepik.com/free-photo/vintage-old-rustic-cutlery-dark_1220-4883.jpg?w=1380&t=st=1690885957~exp=1690886557~hmac=b6c00ada8526ab11154b2b8178dcd37dc8fcc2ed07e8ec1b99efc1135194e14d');
    background-size: cover;
    height: 100vh;
}

/* Center the text both horizontally and vertically */
.third-section h4,
.third-section h3 {
    text-align: center;
    color: white;
    font-weight: bold;
}

.fourth-section {
    padding: 10% 2%;
}

.square-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    /* Make the image cover the square while maintaining aspect ratio */
}

.fifth-section {
    background-color: black;
    color: white;
    

}

.circular-image {
    width: 50%;
    height: 50%;
    object-fit: cover;
    border-radius: 50%; /* Set border-radius to 50% to make the image circular */
}

@media (max-width: 767px) {
  .circular-image {
    width: 100%;
    height: auto;
  }
}


</style>
  
<script scoped>
import navBar from '../global/NavBar.vue';
import footerPage from '../global/FooterPage.vue';

export default {
    name: 'homePage',
    components: {
        navBar,
        footerPage
    },
};
</script>
  
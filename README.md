# First_page
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>

    <div id="sectionhome-page">
        <div class="home-page-bg">
            <h1 class="home-page-heading">Podcasts</h1>
        </div>
        <div class="podcasts-card-container">
            <div class="d-flex flex-row">
                <div id="details-card" onclick="display('sectionPuriJagannadhPodcast')">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="image" />
                    <h1 class="podcast-persons">Puri jaganadh</h1>
                    <p class="episodes">24 Episodes</p>
                </div>
                <div class="sectiontedxtalks" onclick="display('sectiontedxtalks')">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="image" />
                    <h1 class="podcast-persons">Tedx tals</h1>
                    <p class="episodes">12 Episodes</p>
                </div>
            </div>
        </div>
        <div class="podcasts-card-container">
            <div class="d-flex flex-row">
                <div class="sectionsadhguru" onclick="display('sectionsadhgurupodcast')">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="image" />
                    <h1 class="podcast-persons">Sadhguru</h1>
                    <p class="episodes">49pisodes</p>
                </div>
                <div class="sectiononpurpose" onclick="display('sectiononpurposepodcast')">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" class="image" />
                    <h1 class="podcast-persons">On purpose</h1>
                    <p class="episodes">49 Episodes</p>
                </div>
            </div>
        </div>
    </div>
    <div id="sectionPuriJagannadhPodcast">
        <h1 class="podcast-page">Podcast Puri Jaganadh Page:</h1>
        <div class="top-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="podcastimage" />
                <div class="details">
                    <h3 class="details-heading">podcast</h3>
                    <h1 class="podcast-name">Puri Jaganath Podcast</h1>
                    <p class="podcast-caption">The Puri Jaganadh podcast</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">Molecular Gastromy</h1>
                    <p class="episodes-description">Anything happens there it will not cook,...</p>
                    <p class="duration">15 min</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">Mysterious book</h1>
                    <p class="episodes-description">The Voynich manuscript is the 15th century,...</p>
                    <p class="duration">12 min</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">Predator Drone</h1>
                    <p class="episodes-description">The most power full Drone.It is 10 feet height,...</p>
                    <p class="duration">10 min</p>
                </div>
            </div>

        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">Paella</h1>
                    <p class="episodes-description">The natioal dish of spain.It was first star,...</p>
                    <p class="duration">6 min</p>
                </div>
            </div>

        </div>
        <div class="bottom-section">
            <div class="text-right">
                <button class="back-button" onclick="display('sectionhome-page')">Back</button>
            </div>
        </div>
    </div>
    <div id="sectiontedxtalks">
        <h1 class="podcast-page">Podcast Tedx Page:</h1>
        <div class="top-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="podcastimage" />
                <div class="details">
                    <h3 class="details-heading">podcast</h3>
                    <h1 class="podcast-name">The Tedx Podcast</h1>
                    <p class="podcast-caption">The Tedx podcast</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">The section of friction</h1>
                    <p class="episodes-description">Tribology:It's a funny sounding word you might,...</p>
                    <p class="duration">12 min</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">Unleash</h1>
                    <p class="episodes-description">What can we learn from the worlds most enduringly,...</p>
                    <p class="duration">8 min</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">3 psychological tricks</h1>
                    <p class="episodes-description">We all wants to save more money--but overall,...</p>
                    <p class="duration">10 min</p>
                </div>
            </div>

        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">The case for stubborn</h1>
                    <p class="episodes-description">The decade is a moment of choice unlike any we...</p>
                    <p class="duration">12 min</p>
                </div>
            </div>

        </div>
        <div class="bottom-section">
            <div class="text-right">
                <button class="back-button" onclick="display('sectionhome-page')">Back</button>
            </div>
        </div>
    </div>
    <div id="sectionsadhgurupodcast">
        <h1 class="podcast-page">Podcast Sadhguru Page:</h1>
        <div class="top-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="podcastimage" />
                <div class="details">
                    <h3 class="details-heading">podcast</h3>
                    <h1 class="podcast-name">the Sadhguru Podcast</h1>
                    <p class="podcast-caption">The Sadhguru podcast</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">Head or Heart</h1>
                    <p class="episodes-description">Sadhguru shares his wisdom on how to make,...</p>
                    <p class="duration">16 min</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">How to equip yourself</h1>
                    <p class="episodes-description">Society and human interactions are going,...</p>
                    <p class="duration">13 min</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">How not to get irritated</h1>
                    <p class="episodes-description">How do you see an unpleasant spouse the,...</p>
                    <p class="duration">15 min</p>
                </div>
            </div>

        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">Isha Kriya</h1>
                    <p class="episodes-description">Rooted in the timeless wisdom if the yogic,...</p>
                    <p class="duration">16 min</p>
                </div>
            </div>

        </div>
        <div class="bottom-section">
            <div class="text-right">
                <button class="back-button" onclick="display('sectionhome-page')">Back</button>
            </div>
        </div>
    </div>
    <div id="sectiononpurposepodcast">
        <h1 class="podcast-page">Podcast On Purpose Page:</h1>
        <div class="top-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" class="podcastimage" />
                <div class="details">
                    <h3 class="details-heading">podcast</h3>
                    <h1 class="podcast-name">On Purpose with Jay</h1>
                    <p class="podcast-caption">The Jay Shetty podcast</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">Patrick Bet David</h1>
                    <p class="episodes-description">Are you an entrepreneur or have dreams of mental,...</p>
                    <p class="duration">10 min</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">5 Techniques to cope</h1>
                    <p class="episodes-description">Does anxiety looms around every corner of your,...</p>
                    <p class="duration">4 min</p>
                </div>
            </div>
        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">Radhanath Swami ON</h1>
                    <p class="episodes-description">World-renowed spirtual leader and philanthropist,...</p>
                    <p class="duration">12 min</p>
                </div>
            </div>

        </div>
        <div class="bottom-section">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="podcastimage" />
                <div class="container">
                    <h1 class="podcasts">3 ways to let go</h1>
                    <p class="episodes-description">Do the opinions of others veer you from the core,...</p>
                    <p class="duration">13 min</p>
                </div>
            </div>

        </div>
        <div class="bottom-section">
            <div class="text-right">
                <button class="back-button" onclick="display('sectionhome-page')">Back</button>
            </div>
        </div>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>

</html>



@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.home-page-bg {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/podcasts-bg.png");
    background-size: cover;

    height: 30vh;
}

.home-page-heading {
    color: #ffffff;
    padding: 15px;
    padding-bottom: 150px;
    font-size: 30px;
    font-style: "Roboto";
}

.podcasts-card-container {
    padding: 15px;
}

.image {
    height: 22vh;
    width: 180px;
    padding: 15px;
}

.podcast-persons {
    color: #151765;
    padding: 5px;
    font-size: 25px;
    font-style: "Roboto";
    font-weight: 450px;
    margin: 8px;
    text-align: center;
}

.episodes {
    color: #597184;
    padding: 10px;
    font-size: 22px;
    font-style: "Roboto";
    margin: 8px;
    text-align: center;
}

.podcast-page {
    color: #597184;
    font-family: Roboto;
    font-size: 20px;
    padding-bottom: 10px;
}

.top-section {
    background-color: #151765;
    background-size: cover;
    height: 30vh;
    width: 500px;
}

.podcastimage {
    height: 30vh;
    width: 200px;
    padding: 15px;
    padding-top: 30px;
}

.details-heading {
    color: #ffffff;
    font-family: Roboto;
    font-size: 14px;
    padding-top: 30px;
}

.podcast-name {
    color: #ffffff;
    font-family: Roboto;
    font-size: 34px;
    padding-top: 12px;
    font-weight: bold;
}

.podcast-caption {
    color: #ffffff;
    font-family: Roboto;
    font-size: 14px;
    padding: 6px;
}

.bottom-section {
    background-color: #ffffff;
    background-size: cover;
    height: 30vh;
    width: 500px;
}

.podcasts {
    color: #151765;
    padding-top: 20px;
    font-size: 20px;
    font-style: "Roboto";
    font-weight: bold;
    margin: 10px
}

.episodes-description {
    color: #597184;
    padding: 10px;
    font-size: 18px;
    font-style: "Roboto";
    margin: 8px;
}

.duration {
    color: #151765;
    padding-top: 20px;
    font-size: 15px;
    font-style: "Roboto";
    font-weight: bold;
    margin: 10px
}

.back-button {
    color: #ffffff;
    font-family: Roboto;
    font-size: 12px;
    border-radius: 16px;
    padding: 6px;
    height: 32px;
    width: 85px;
    background-color: #151765;
    margin: 7px;

}

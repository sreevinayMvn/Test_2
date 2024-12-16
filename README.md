 <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PETA - Investment Management Profiles</title>
    <link href="https://fonts.googleapis.com/css2?family=Bree+Serif&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="media.css">
    <link rel="shortcut icon" href="Images/PETA-Fav.png" type="image/x-icon">

    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 20px;
            background-image: url("C:/Users/mvn.sreevinay/OneDrive - S&P Global/Documents/IMP-Projects/PETA-Investment_Management_Profiles/Inputs/491362538070.jpg");
            background-size: cover; /* Ensures the background covers the entire page */
            background-repeat: no-repeat; /* Prevents the image from repeating */
            background-attachment: fixed; /* Keeps the background fixed while scrolling */
            background-position: center; /* Centers the background image */
        }

        .logo {
            position: absolute;
            top: 20px;
            left: 20px;
            width: 100px;
            height: auto;
            z-index: 10;
        }

        .header-container {
            background-color: rgba(255, 255, 255, 0.9);
            padding: 20px;
            text-align: center;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
            position: relative;
        }

        .header-title {
            font-size: 32px;
            color: #E03C31;
            margin: 0;
            font-weight: 700;
        }

        .current-date-container {
            font-size: 14px;
            color: #000000;
            text-align: right;
            margin-top: 10px;
        }

        .modified-info {
            color: #FFFFFF;
        }

        .search-container {
            position: absolute;
            top: 20px; /* Adjust based on your layout */
            right: 20px; /* Adjust based on your layout */
            display: flex;
            align-items: center;
        }

        .search-input {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            outline: none;
        }

        .search-button {
            background-color: transparent;
            border: none;
            cursor: pointer;
            margin-left: 5px;
        }

        .search-icon {
            width: 20px; /* Adjust size as needed */
            height: auto;
        }

        .container-wrapper {
            display: flex;
            flex-wrap: wrap;
            justify-content: center; /* Center the containers */
            margin-top: 80px;
        }

        .container {
            background-color: rgba(255, 255, 255, 0.7); /* Reduced opacity */
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin: 10px;
            flex: 1 1 45%;
            max-width: 45%;
            box-sizing: border-box;
            transition: transform 0.3s, box-shadow 0.3s;
            text-align: center;
            opacity: 0;
            animation: fadeIn 0.5s forwards; /* Added animation */
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .container:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
        }

        h1 {
            font-size: 24px;
            color: #E03C31;
            margin-bottom: 10px;
            font-weight: 700;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.3); /* Added text shadow */
            letter-spacing: 1px; /* Added letter spacing */
        }

        h2 {
            font-size: 18px;
            color: #000000;
            margin: 5px 0;
            font-weight: normal;
            text-align: left;
        }

        h2 a {
            text-decoration: none;
            color: #000000;
            transition: background-color 0.3s, color 0.3s;
            display: block;
            margin-left: 20px;
            padding: 10px;
            border: 1px solid #000000;
            border-radius: 5px;
            margin-bottom: 5px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2), -2px -2px 5px rgba(255, 255, 255, 0.7);
        }

        h2 a:hover {
            background-color: #D3D3D3; /* Highlight color */
            color: #E03C31; /* Change text color on hover */
            text-decoration: underline;
            box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.3), -4px -4px 5px rgba(255, 255, 255, 0.7);
        }

        .note {
            margin-top: 20px;
            font-size: 14px;
            color: #FFFFFF;
            text-align: center;
            padding: 10px; /* Add padding for better appearance */
            border-radius: 5px; /* Rounded corners */
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                flex: 1 1 100%;
                max-width: 100%;
            }
        }
    </style>
</head>

<body>
    <img src="C:/Users/mvn.sreevinay/OneDrive - S&P Global/Documents/IMP-Projects/PETA-Investment_Management_Profiles/Inputs/Logo_v1.1.png" alt="PETA Logo" class="logo">

    <div class="header-container">
        <h1 class="header-title">PETA - Weblinks and Guidelines</h1>
        <div class="current-date-container" id="currentDate"></div>
        
        <!-- Search Container -->
        <div class="search-container">
            <input type="text" placeholder="Search..." class="search-input" id="searchInput" onkeyup="searchFunction()">
            <button class="search-button">
                <img src="C:/Users/mvn.sreevinay/OneDrive - S&P Global/Documents/IMP-Projects/PETA-Investment_Management_Profiles/Inputs/Search Icon.png" alt="Search" class="search-icon">
            </button>
        </div>
    </div>

    <div class="container-wrapper" id="containerWrapper">
        <!-- Right Side Containers -->
        <div class="container">
            <h1>Process Essentials</h1>
            <h2><a href="https://prdmkapp-citrix.info.corp/Citrix/prdmkappWeb/" target="_blank">Orion</a></h2>
            <h2><a href="https://prdmkapp-citrix.info.corp/Citrix/prdmkappWeb/" target="_blank">Orion 2.0</a></h2>
            <h2><a href="https://ihsmarkit.cerb.me/login?url=pages%2F113-Deals-Transactional" target="_blank">Cerb</a></h2>
            <h2><a href="https://adviserinfo.sec.gov/" target="_blank">IAPD</a></h2>
            <h2><a href="https://www.sedarplus.ca/landingpage/" target="_blank">SEDAR</a></h2>
            <h2><a href="https://www.sec.gov/" target="_blank">SEC</a></h2>
            <h2><a href="https://www.sec.gov/edgar/searchedgar/mutualsearch.htm" target="_blank">SEC Mutual Fund Search</a></h2>
            <h2><a href="https://search.gleif.org/#/search/" target="_blank">LEI</a></h2>
            <h2><a href="https://brokercheck.finra.org/" target="_blank">Broker Check</a></h2>
            <h2><a href="https://register.fca.org.uk/s/" target="_blank">UK Registry</a></h2>
        </div>

        <div class="container">
            <h1>Sparks</h1>
            <h2><a href="https://spark.spglobal.com/assist" target="_blank">Spark Home</a></h2>
            <h2><a href="https://spark.spglobal.com/assist?spark_id=14679" target="_blank">SMP Finder 1.1</a></h2>
            <h2><a href="https://spark.spglobal.com/assist?spark_id=15885" target="_blank">Fund Finder 1.0</a></h2>
        </div>

        <div class="container">
            <h1>S&P Global Essentials</h1>
            <h2><a href="https://sphere.spglobal.com/" target="_blank">Sphere</a></h2>
            <h2><a href="https://spgi.service-now.com/esc" target="_blank">mySolution Portal</a></h2>
            <h2><a href="https://learning.spglobal.com/lmt/lmtLogin.prMenu?in_sessionid=5AA5823390882JJ4" target="_blank">Learning Xchange</a></h2>
            <h2><a href="https://spgi.service-now.com/esc?id=emp_taxonomy_topic&topic_id=c9cc06219763ad50b2d3bc77f053af96" target="_blank">Report an IT Issue</a></h2>
            <h2><a href="https://cmms.serviceinsight.cbre.com/requests" target="_blank">Submit a Facilities Request</a></h2>
            <h2><a href="https://www.capitaliq.com/CIQDotNet/Login-okta.aspx" target="_blank">S&P Capital IQ Platform</a></h2>
            <h2><a href="https://www.capitaliq.spglobal.com/web/login?#/" target="_blank">Capital IQ Pro</a></h2>
        </div>

        <div class="container">
            <h1>S&P Global Policies</h1>
            <h2><a href="https://spd.spgbenefits.com/Document/ViewPublicPage/354b2341-ca74-41e2-b89f-b102a9929af9" target="_blank">India Holiday Schedule 2025</a></h2>
            <h2><a href="https://spgi.service-now.com/esc?id=kb_article&sysparm_article=KB0142867" target="_blank">India Leave Policy</a></h2>
            <h2><a href="https://spgi.service-now.com/esc?id=kb_article&sysparm_article=KB0142792" target="_blank">India Leave without Pay Policy</a></h2>
            <h2><a href="https://spgi.service-now.com/esc?id=kb_article&sysparm_article=KB0142846" target="_blank">India Parental Leave Policy</a></h2>
            <h2><a href="https://spgi.service-now.com/esc?id=kb_article&sysparm_article=KB0142874" target="_blank">Global Compassion Leave</a></h2>
            <h2><a href="https://spgi.service-now.com/esc?id=kb_article&sysparm_article=KB0142790" target="_blank">Global Sabbatical Leave</a></h2>
            <h2><a href="https://spgi.service-now.com/esc?id=kb_article&sysparm_article=KB0142759" target="_blank">Global Education Support Policy</a></h2>
            <h2><a href="https://spgi.service-now.com/esc?id=kb_article_view&sysparm_article=KB0142866" target="_blank">Global Employee Referral Program</a></h2>
            <h2><a href="https://spgi.service-now.com/esc?id=kb_article&sysparm_article=KB0142879" target="_blank">Global Wellbeing Support Program</a></h2>
            <h2><a href="https://spgi.service-now.com/esc?id=kb_article&sysparm_article=KB0142835" target="_blank">India Day Care Policy</a></h2>
        </div>
    </div>

    <!-- Current Date and Last Modified Info -->
    <div class="current-date-container">
        <div id="currentDate"></div>
        <div class="modified-info" id="lastModified"></div>
    </div>

    <!-- Training & Guidelines Button -->
    <div class="container" style="flex: 1 1 100%; max-width: 100%; text-align: center;">
        <h1><a href="Trainings&Guidelines_v1.1.html" target="_blank">Training & Guidelines</a></h1>
    </div>

    <div class="note">
        *Note for Internal Use only
    </div>

    <script>
        function updateCurrentDate() {
            const now = new Date();
            const optionsDate = { day: '2-digit', month: '2-digit', year: 'numeric' };
            const currentDate = now.toLocaleDateString('en-GB', optionsDate);
            document.getElementById("currentDate").innerHTML = `Date: ${currentDate}`;

            const lastModifiedUser = "Modified by: Sree vinay Mvn";
            const lastModifiedDate = `Last Modified: ${now.toLocaleString('en-GB', { dateStyle: 'short', timeStyle: 'short' })}`;
            document.getElementById("lastModified").innerHTML = `<span class="modified-info">${lastModifiedUser} | ${lastModifiedDate}</span>`;
        }

        function searchFunction() {
            const input = document.getElementById('searchInput');
            const filter = input.value.toLowerCase();
            const containers = document.getElementsByClassName('container');

            for (let i = 0; i < containers.length; i++) {
                const links = containers[i].getElementsByTagName('h2');
                let found = false;

                for (let j = 0; j < links.length; j++) {
                    const linkText = links[j].textContent || links[j].innerText;
                    if (linkText.toLowerCase().indexOf(filter) > -1) {
                        links[j].style.display = ""; // Show link
                        found = true;
                    } else {
                        links[j].style.display = "none"; // Hide link
                    }
                }

                // Show or hide the container based on whether any link was found
                containers[i].style.display = found ? "" : "none";
            }
        }

        updateCurrentDate(); // Initial call
    </script>
</body>

</html>

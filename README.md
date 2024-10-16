<head>
    <!-- Importing Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&family=Roboto:wght@300;400&display=swap" rel="stylesheet">

    <style>

        body {
            font-family: 'Roboto', sans-serif;
            font-weight: 300; /* Use a light font for body text */
            color: #333;
            margin: 20px;
            line-height: 1.8;
        }

h1 {   
    font-family: 'Lora', serif; /* Modern serif font Lora */
    font-size: 1.5em; /* Adjust the size */
    font-weight: 400; /* Regular weight */
    color: #2c3e50;
    margin-bottom: 10px;
}

h2 {   
    font-family: 'Lora', serif; /* Lora for h2 */
    font-size: 20px;
    font-weight: 400; /* Regular weight */
    color: #2c3e50;
    margin-bottom: 10px;
}

        hr {
            border: 0;
            border-top: 1px solid #bbb;
            margin: 20px 0;
        }

        /* Remove left spacing for ordered lists */
        ol {
            font-size: 18px;
            line-height: 1.8;
            margin-left: 0; /* Remove left margin */
            padding-left: 0; /* Remove left padding */
            color: #4d4d4d;
        }

a {
    text-decoration: none;
    color: #007c91; /* Ocean blue-teal */
    transition: color 0.3s ease;
}

a:hover {
    color: #006672; /* Darker ocean teal on hover */
}

        section {
            margin-bottom: 40px;
        }

        .container {
            max-width: 1200px; /* Increase the maximum width */
            margin: 0 auto; /* Center the content */
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
        }

        li {
            margin-bottom: 15px;
        }

        /* Flexbox for responsive layout */
        .flex-container {
            display: flex;
            flex-wrap: nowrap; /* Ensure items don't wrap */
            align-items: flex-start; /* Align items to the top */
            overflow: hidden;
        }

        .content {
            flex: 1;
            min-width: 250px;
            margin-left: 30px; /* Add margin to push content right */
            margin-top: 0; /* Remove extra spacing at the top */
        }

        .content p {
            margin-top: 0; /* Remove margin above paragraph */
            padding-top: 0; /* Remove padding above paragraph */
        }

        /* Desktop view: Ensure text is left-aligned */
        div[style*="flex: 1;"] p {
            text-align: left; /* Left-align text on desktop */
        }

        /* Add spacing between text and image */
        .image-crop {
            margin-left: 20px; /* Add spacing between text and image */
        }

        /* Override the color for Dongho Song */
        h1 a {
            color: #2c3e50; /* Ensure link color is the same as normal text */
        }

        /* Responsive design for mobile */
        @media (max-width: 768px) {
            .image-crop {
                margin-left: 0;
                margin-top: 20px; /* Add spacing above the image on mobile */
                width: 100%; /* Ensure image fills the width properly on mobile */
            }

            /* Make the layout vertical on smaller screens */
            div[style*="display: flex;"] {
                flex-direction: column;
                align-items: center;
            }

            /* Ensure text is centered on mobile */
            div[style*="flex: 1;"] p {
                text-align: center; /* Center-align text on mobile */
            }
        }
    </style>
</head>

<div style="display: flex; align-items: flex-start; justify-content: space-between; gap: 20px; flex-wrap: wrap;">
    <div style="flex: 1; min-width: 200px;">
        <p style="margin: 0; padding: 0; font-size: 1.2em; text-align: left;">
            Associate Professor of Finance<br>
            Johns Hopkins University<br>
            Carey Business School<br>
        </p>
        <p style="margin-top: 20px; font-size: 1.2em; text-align: left;">
            <!-- Email first -->
            <a href="mailto:dongho.song@jhu.edu">
                dongho.song@jhu.edu
            </a>
            <br>
            <!-- CV link second -->
            <a href="https://www.dropbox.com/scl/fi/24w0wsai88q1725l73xho/DonghoSong-CV.pdf?rlkey=vfe2hbq6pua4apthvi3whmtwy&st=bf0i2ug0&dl=0" target="_blank">
                <i class="fas fa-envelope"></i> CV
            </a>
            &nbsp;|&nbsp;
            <!-- Google Scholar link third -->
            <a href="https://scholar.google.com/citations?user=z9TGeXYAAAAJ&hl=en" target="_blank">
                <i class="fas fa-graduation-cap"></i> Google Scholar
            </a>
        </p>
    </div>
    <div class="image-crop" style="flex-shrink: 0;">
        <!-- Adjust image size -->
<img src="https://raw.githubusercontent.com/donghosongd/donghosongd.github.io/blob/f1a7ef7785469b0b4acb7e1999c34e604e05bd49/dsong.jpg" alt="Dongho Song" style="width: 250px; max-width: 100%; height: auto;">
    </div>
</div>



<h2>Working Papers</h2>

<ol>
    <li>
        <a href="https://www.dropbox.com/scl/fi/q9t99q4q7p9jei6fxkfqm/election_draft_es.pdf?rlkey=u5mazbch5zv6bp2kkm76e6m46&st=2xa6n46k&dl=0" target="_blank" rel="noopener noreferrer">The Comovement of Voter Preferences: Insights from U.S. Presidential Election Prediction Markets Beyond Polls</a>, 
        with Vadim Elenev, 2024
    </li>
    <li>
<a href="https://www.dropbox.com/scl/fi/4w9etfnrgrrnqvw48odaw/Fragmentation.pdf?rlkey=daw0sywgctbqy1olip9cd14ox&st=z89i156x&dl=0" target="_blank" rel="noopener noreferrer">
    Are We Fragmented Yet? Measuring Geopolitical Fragmentation and Its Causal Effects
</a>, with Jesús Fernández-Villaverde and Tomohide Mineyama, 2024 &nbsp; &nbsp; 
    [<a href="https://www.dropbox.com/scl/fi/he6faychjg86negnepcg8/fragmentation-index.xlsx?rlkey=fkzmpg116sq5qtb9gvbqccoq4&st=thj6pxxr&dl=0" target="_blank" rel="noopener noreferrer">
    Geopolitical Fragmentation Index
</a>]
    </li>
    <li>
        <a href="https://www.dropbox.com/scl/fi/ucsqyoeh1x8i8kbfz8de8/BianchiNicoloSong_inflation_bc_Full_paper.pdf?rlkey=p2sftb0qzqvtk6ln18ozxg9b3&st=fbthgd5r&dl=0" target="_blank" rel="noopener noreferrer">Inflation and Real Activity over the Business Cycle</a>, 
        with Francesco Bianchi and Giovanni Nicolò, 2024
        <br>(<em>Review of Economic Studies</em>, R&R)
    </li>
    <li>
        <a href="https://www.dropbox.com/scl/fi/08waf5zhfg8iagvuo9jxw/CLS_COV_latest.pdf?rlkey=sl6tkvktg9aq3hkfgicjcr6ef&st=4s91sp41&dl=0" target="_blank" rel="noopener noreferrer">The Real Channel for Nominal Bond-Stock Puzzles</a>, 
        with Mikhail Chernov and Lars Lochstoer, 2023
        <br>(<em>Journal of Finance</em>, R&R)
    </li>
    <li>
        <a href="https://www.dropbox.com/scl/fi/71k2dtgutklgneydktr2k/draft_DSY2023_latest.pdf?rlkey=mcnqtsr517t83j2zop8fg4sy5&st=m3fu1yug&dl=0" target="_blank" rel="noopener noreferrer">Deciphering Federal Reserve Communication via Text Analysis of Alternative FOMC Statements</a>, 
        with Taeyoung Doh and Shu-Kuei Yang, 2023
        <br>(<em>American Economic Journal: Macroeconomics</em>, R&R)
    </li>
    <li>
        <a href="https://www.dropbox.com/scl/fi/6viaoh5c6by29tiqslpl3/DGS_draft_latest_RWP.pdf?rlkey=qjfe1djr28i76rahl9eujhohl&st=bh45y0d0&dl=0" target="_blank" rel="noopener noreferrer">Leaning Against the Data: Policymaker Communications under State-based Forward Guidance</a>, 
        with Taeyoung Doh and Joseph Gruber, 2022
    </li>
</ol>


<h2>Publications</h2>

<ol>
    <li>
        <a href="https://onlinelibrary.wiley.com/doi/full/10.1111/jofi.13336" target="_blank" rel="noopener noreferrer">The Term Structure of Covered Interest Rate Parity Violations</a>, 
        with Patrick Augustin, Mikhail Chernov, Lukas Schmid, 
        <em>Journal of Finance</em>, 2024, Volume 79, Issue 3, pp. 2077-2114 
    </li>
    <li>
        <a href="https://www.sciencedirect.com/science/article/abs/pii/S0304405X24000138" target="_blank" rel="noopener noreferrer">Fearing the Fed: How Wall Street Reads Main Street</a>, 
        with Vadim Elenev, Tzuo Law, and Amir Yaron, 
        <em>Journal of Financial Economics</em>, 2024, Volume 153, 103790 
    </li>
    <li>
        <a href="https://www.ijcb.org/journal/ijcb24q4a5.pdf" target="_blank" rel="noopener noreferrer">Real-Time Forecasting with a (Standard) Mixed-Frequency VAR During a Pandemic</a>, 
        with Frank Schorfheide, 
        <em>International Journal of Central Banking</em>, 2024, Volume 20, Number 4, pp. 275-320 
    </li>
    <li>
        <a href="https://www.sciencedirect.com/science/article/pii/S0165188922002846" target="_blank" rel="noopener noreferrer">The Long-Term Impact of the COVID-19 Unemployment Shock on Life Expectancy and Mortality Rates</a>, 
        with Francesco Bianchi and Giada Bianchi, 
        <em>Journal of Economic Dynamics and Control</em>, 2023, Volume 146, 104581 
    </li>
    <li>
        <a href="https://www.tandfonline.com/doi/full/10.1080/07350015.2022.2097912?journalCode=ubes20" target="_blank" rel="noopener noreferrer">News-Driven Uncertainty Fluctuations</a>, 
        with Jenny Tang, 
        <em>Journal of Business and Economic Statistics</em>, 2023, Volume 41, Issue 3, pp. 968-982 
    </li>
    <li>
        <a href="https://www.sciencedirect.com/science/article/pii/S0304405X21002361?via%3Dihub" target="_blank" rel="noopener noreferrer">The Term Structure of Equity Risk Premia</a>, 
        with Ravi Bansal, Shane Miller, and Amir Yaron, 
        <em>Journal of Financial Economics</em>, 2021, Volume 142, Issue 3, pp. 1209-1228 
    </li>
    <li>
        <a href="https://www.sciencedirect.com/science/article/pii/S0304405X20302841" target="_blank" rel="noopener noreferrer">Benchmark Interest Rates when the Government is Risky</a>, 
        with Patrick Augustin, Mikhail Chernov, and Lukas Schmid, 
        <em>Journal of Financial Economics</em>, 2021, Volume 140, Issue 1, pp. 74-100 
    </li>
    <li>
        <a href="https://www.sciencedirect.com/science/article/abs/pii/S0304405X19302922?via%3Dihub" target="_blank" rel="noopener noreferrer">Sovereign Credit Risk and Exchange Rates: Evidence from CDS Quanto Spreads</a>, 
        with Patrick Augustin and Mikhail Chernov, 
        <em>Journal of Financial Economics</em>, 2020, Volume 137, Issue 1, pp. 129-151 
    </li>
    <li>
        <a href="https://onlinelibrary.wiley.com/doi/abs/10.3982/ECTA14308" target="_blank" rel="noopener noreferrer">Identifying Long-Run Risks: A Bayesian Mixed-Frequency Approach</a>, 
        with Frank Schorfheide and Amir Yaron, 
        <em>Econometrica</em>, 2018, Volume 86, Issue 2, pp. 617-654 
    </li>
    <li>
        <a href="https://academic.oup.com/rfs/article/30/8/2761/3788530" target="_blank" rel="noopener noreferrer">Bond Market Exposures to Macroeconomic and Monetary Policy Risks</a>, 
        <em>Review of Financial Studies</em>, 2017, Volume 30, Issue 8, pp. 2761-2817 
    </li>
    <li>
        <a href="https://www.sciencedirect.com/science/article/abs/pii/S0304407615002857" target="_blank" rel="noopener noreferrer">Improving GDP Measurement: A Measurement-Error Perspective</a>, 
        with Borağan Aruoba, Francis Diebold, Jeremy Nalewaik, and Frank Schorfheide, 
        <em>Journal of Econometrics</em>, 2016, Volume 191, Issue 2, pp. 384-397 
    </li>
    <li>
        <a href="https://www.tandfonline.com/doi/abs/10.1080/07350015.2014.954707" target="_blank" rel="noopener noreferrer">Real-time Forecasting with a Mixed-Frequency VAR</a>, 
        with Frank Schorfheide, 
        <em>Journal of Business and Economic Statistics</em>, 2015, Volume 33, Issue 3, pp. 366-380 
    </li>
</ol>


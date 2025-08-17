"# Capstone-Project-Sutan" 

Email                   : sutandami@gmail.com

Title Project           : **AI-Powered Sentiment Classification and Insight Analysis of Indonesian Government Mobile Apps Reviews for Public Service Improvement**

Project Overview        :

The global digital transformation over the past two decades has significantly changed the way people access information, interact, and obtain public services. This phenomenon has also occurred in Indonesia, where the government strives to adopt digital technologies to improve service efficiency and transparency. However, the rapid pace of digitalization has also created major challenges. According to data from the Ministry of State Apparatus Utilization and Bureaucratic Reform (KemenPAN-RB), there are more than 27,000 government-owned applications managed by various ministries, agencies, and local governments. Each year, a large budget is allocated to maintain these applications, yet not all are utilized optimally (Idris, 2023). Many of them have overlapping functions, poor user interfaces, or servers that are rarely accessed by the public (Yanwardhana, 2024). This situation not only leads to wasteful public spending but also opens opportunities for structural inefficiencies and potential misuse of funds. In some cases, the procurement or development of irrelevant or underperforming applications can pave the way for cost mark-ups, fictitious projects, or collusion with vendors, ultimately harming state finances and hindering the quality of public services.

This project aims to contribute to improving the quality of digital public services through an AI-powered sentiment classification and insight analysis approach. The main goal is to systematically evaluate user reviews and feedback on Indonesian government mobile applications. Data will be collected from legal and publicly available sources that is Google Play Store. Next, Natural Language Processing (NLP) techniques will be applied, including the use of Large Language Models (LLMs) with the IBM Granite Model, to classify reviews into positive, neutral, and negative sentiment categories. Furthermore, insight extraction analysis will identify key issues, user complaints, and recurring suggestions. This approach ensures that every citizen's opinion can be transformed into measurable and relevant strategic information.

The outcome of this project is expected to provide accurate, data-driven insights that are easy to understand for stakeholders from application developers to policymakers. With this information, they can identify the most urgent service gaps to address, prioritize the development of the most needed features, and formulate well-directed, actionable improvement strategies. In the long term, this initiative aims to increase public trust in government digital services, optimize the use of technology budgets, and promote the creation of an efficient, integrated, and truly beneficial government application ecosystem for the wider community. In other words, this project is not merely about data analysis it is a concrete step towards a more responsive, user-centered digital government transformation.

References              :

Idris, Muhammad. (2023, March). Pemborosan Anggaran, Ada 27.000 Aplikasi Milik Pemerintah Lewat Vendor. https://money.kompas.com/read/2023/03/20/193607826/pemborosan-anggaran-ada-27000-aplikasi-milik-pemerintah-lewat-vendor.

Yanwardhana, Emir. (2024, May). Jokowi Kecewa Pusat & Daerah Habiskan Rp6,2 T Buat Bikin Aplikasi. https://www.cnbcindonesia.com/news/20240527151234-4-541502/jokowi-kecewa-pusat-daerah-habiskan-rp62-t-buat-bikin-aplikasi?


Raw Dataset Link        :

        Format link get data review app from Google Play with Library google_play_scraper (Python) :

        https://play.google.com/store/apps/details?id=<package_name>
         
        Gov Indonesian Mobile Apps Link Dataset on Google Play Store :

        1. SATUSEHAT - PeduliLindungi --> https://play.google.com/store/apps/details?id=com.telkom.tracencare
        2. JAKI - Jakarta Kini --> https://play.google.com/store/apps/details?id=id.go.jakarta.smartcity.jaki
        3. Identitas Kependudukan Digital --> https://play.google.com/store/apps/details?id=gov.dukcapil.mobile_id
        4. M-Paspor --> https://play.google.com/store/apps/details?id=id.go.imigrasi.paspor_online
        5. Jamsostek Mobile - BPJSTKU --> https://play.google.com/store/apps/details?id=com.bpjstku
        6. MySAPK BKN --> https://play.google.com/store/apps/details?id=com.nudi.bkn.sapk
        7. SiCantik Cloud --> https://play.google.com/store/apps/details?id=id.go.perizinan.sicantikcloud
        8. Mobile JKN --> https://play.google.com/store/apps/details?id=app.bpjs.mobile
        9. Cek Bansos --> https://play.google.com/store/apps/details?id=id.go.kemensos.pelaporan
        10. PLN Mobile --> https://play.google.com/store/apps/details?id=com.icon.pln123
        11. MyPertamina --> https://play.google.com/store/apps/details?id=com.dafturn.mypertamina
        12. Pegadaian Digital --> https://play.google.com/store/apps/details?id=com.pegadaiandigital
        13. Digital Korlantas POLRI --> https://play.google.com/store/apps/details?id=id.qoin.korlantas.user
        14. SIGNAL - Samsat Digital Nasional --> https://play.google.com/store/apps/details?id=app.signal.id
        15. POLRI PRESISI --> https://play.google.com/store/apps/details?id=superapps.polri.presisi.presisi
        16. Mobile JKN Faskes - BPJS Kesehatan --> https://play.google.com/store/apps/details?id=app.bpjs.mobilefaskes
        17. OSS Indonesia --> https://play.google.com/store/apps/details?id=id.go.oss
        18. Info BMKG --> https://play.google.com/store/apps/details?id=com.Info_BMKG
        19. Sentuh Tanahku --> https://play.google.com/store/apps/details?id=id.go.bpn.sentuh
        20. JDIH Kemensos --> https://play.google.com/store/apps/details?id=id.go.kemensos.jdih.jdih_kemensos_f
        21. LMS Kemendes --> https://play.google.com/store/apps/details?id=com.mid.lmskemendes
        22. Internal POLRI --> https://play.google.com/store/apps/details?id=superapps.polri.internal.presisi
        23. Pemutakhiran PK - BKKBN --> https://play.google.com/store/apps/details?id=com.yosicsa.pemutakhiranpk
        24. SIKS Mobile --> https://play.google.com/store/apps/details?id=id.go.kemensos.sagismobile
        25. M-Pajak --> https://play.google.com/store/apps/details?id=id.go.pajak.djp
        26. iPusnas --> https://play.google.com/store/apps/details?id=mam.reader.ipusnas
        27. SIMPKB --> https://play.google.com/store/apps/details?id=id.simpkb.app
        28. Jaga - KPK --> https://play.google.com/store/apps/details?id=id.or.checkmy
        29. Satudikti - Kemdikbud --> https://play.google.com/store/apps/details?id=id.satudikti.app
        30. IDENTIK PKH Kementan - Peruri --> https://play.google.com/store/apps/details?id=com.solusibejo.hiternak
        31. BPKH Apps --> https://play.google.com/store/apps/details?id=id.go.bpkh.nmva
        32. AK23 Online by Pusinafis POLRI --> https://play.google.com/store/apps/details?id=com.ak23.online
        33. GTK Kemenag --> https://play.google.com/store/apps/details?id=id.siap.ptk

Analysis Process        :

        1. Data Collection      :

            - Identify a list of Indonesian government mobile applications across various ministries and sectors.
            - Retrieve publicly available user reviews from Google Play Store using scraping libraries (google-play-scraper).
            - Gather review metadata including:
                + App name
                + Username
                + Rating score
                + Review text
                + Review date

        2. Data Preprocessing   :

            - Remove duplicate entries: Prevents bias in the model's analysis caused by repeated reviews.
            - Clean special/invalid characters: Remove or replace corrupted encodings, excessive whitespace, or stray symbols while keeping meaningful punctuation intact.
            - Optional light cleanup: Standardize spacing, normalize quotation marks, but avoid altering sentence case or removing punctuation.

        3. AI-Powered Analysis  :

            - Sentiment Classification:
                + The LLM classifies each user review into Positive, Neutral, or Negative sentiment categories.
                + This structured classification enables quantitative sentiment distribution analysis (count and percentage) and facilitates the detection of the overall public perception toward each application.

            - Summarization:
                + The LLM generates concise summaries highlighting recurring issues, feature requests, and positive feedback.
                + This provides stakeholders with a quick understanding of the main discussion points without the need to manually read thousands of reviews.

            - Text-Based Insight Extraction and Data Visualization:
                + The LLM identifies patterns, frequently mentioned keywords, and thematic topics such as bugs, login issues, OTP errors, performance problems, usability concerns, security issues, and policy compliance matters.
                + These insights are further visualized through bar charts and pie charts to reveal sentiment trends and issue frequency, supporting actionable recommendations for improving public service quality in the digital sector.
        
        4. Insight and Findings : 
            analytical result, logical explanation, and unique.

        5. Conclusion and Recommendation    :
            Recommendation for Indonesian Government, developer vendors, and other stakeholders to enhance public service quality in digital technologies Mobile Apss.

Insight and Findings    :

        Workflow Process:
        1. Data Collection (Scraping Reviews):
            - When reviews are taken from all applications, the number of reviews per application is equal (e.g., 5 reviews x 33 apps = 165 total reviews).
            - When focusing on a specific target application, 100 of the latest reviews are classified to capture sentiment trends for that app.
        2. Preprocessing: Duplicate reviews are removed to avoid bias and ensure cleaner data.
        3. Classification with IBM Granite Model: The dataset is split into several batches (1 batch = 100 reviews).
        4. Classification & Summarization are performed in three levels:
            - Sentiment Classification per Review
            - Sentiment Classification per Review per Application (automated & manual for specific apps)
            - Sentiment Classification per Review per APK Label (Issue/Problem category)
            - Sentiment Classification per Review per Application per APK Label (multi-label / cross classification)
        

        Key Findings & Analytical Insights
            1. Sentiment Classification per Review

                a. Distribution:
                    - Positive = 62 (37.35%)
                    - Negative = 78 (46.99%)
                    - Neutral = 26 (15.66%)

                b. General Observations:
                    - Negative reviews dominate, mainly citing errors, slow performance, crashes, and login failures.
                    - Positive reviews are still significant (over one-third), highlighting usefulness and practicality (e.g., "easy to use", "helpful").
                    - Neutral reviews are minimal, often a mix of praise + suggestions.

                c. Insights:
                    - Negative dominance: Ratio Negative:Positive = 1.25 : 1 -> shows strong potential to shift perception if technical issues are fixed.
                    - High expectations: Low neutral percentage suggests users lean toward extremes (highly satisfied vs. highly dissatisfied).
                    - Sentiment patterns:
                        + Positives = utility (faster access, simplicity).
                        + Negatives = technical failures in core features.
                        + Neutral = appreciation + constructive feedback.

                d. Implications & Recommendations:
                    - Quick Wins: Prioritize bug fixes, login, and app stability.
                    - Long-term Strategy: Educate users, add requested features, and maintain consistent quality to strengthen trust.

            2. Sentiment Classification per Review per Application
                
                a. Distribution:
                    - Positive = 61 (36.53%)
                    - Negative = 80 (47.90%)
                    - Neutral = 26 (15.57%)
                    
                    (Note: Model miscounted by +2 reviews; does not affect overall distribution.)

                b. General Observations:
                    - Most government apps lean negative, especially core service apps (identity, health, education).
                    - Some apps maintain balanced or positive sentiment (e.g., Pegadaian Digital, SIMPKB, JDIH Kemensos).
                    - Worst-performing apps by sentiment score (Positive -> Negative):
                        (1) IKD (Digital ID) = -5
                        (2) Pemuktahiran PK - BKKBN = -5
                        (3) Satudikti - Kemendikbud = -5
                        (4) SiCantik Cloud - Kominfo = -5
                        (5) Jamsostek Mobile (BPJSTKU) = -4
                    - SiCantik Cloud, intended as a flagship government licensing system, ironically shows poor performance (login failures, slow response, repeated errors).

                c. Insights:
                    - Polarization across apps: clear divide between apps with strong positives vs. strong negatives.
                    - Weakest segments = Identity & Education apps, both core services.
                    - Common pain points: login/authentication failures, crashes, confusing UX, and frustration due to high expectations.
                    
                d. Implications & Recommendations:
                    - Validate findings with new data: re-scrape 50 latest reviews per worst app (5 apps x 50 = 250 reviews).
                    - Quick Wins: address login and crash issues in the worst-performing apps.
                    - Long-term: periodic monitoring, stronger QA/testing, and benchmarking against successful apps.

            
            3. Sentiment Classification per Review per APK Label (Issue/Problem)
                
                a. Distribution:
                    - Positive = 71 (43.03%)
                    - Negative = 87 (52.73%)
                    - Neutral = 7 (4.24%)

                b. General Observations:
                    - Negative sentiment dominates (>50%), with most issues linked to login failures.
                    - Positive reviews emphasize benefits despite technical issues.
                    - Neutral reviews are rare and usually "praise + suggestion".
                    Top recurring issues:
                        + Login failure = 17 reviews (10.3%)
                        + Errors, password issues = ~4 reviews each
                        + Others (bug, crash, server down, OTP, payment, etc.) = <3 reviews each

                c. Insights:
                    - Login = critical weak point, with >10% of all reviews citing it.
                    - Reliability of core features (login, password, server stability) heavily influences sentiment.
                    - Trust vs. frustration: although many users complain, there is still strong trust/support for government's digitalization efforts.

                d. Implications & Recommendations:
                    - Quick Wins: fix login/authentication modules, provide clearer error messages, strengthen QA.
                    - Long-term: server reliability upgrades, security enhancements, better user support (chatbot/FAQ/helpdesk).
                            
            4. Sentiment Classification per Review per Label per Application
                
                a. Findings:
                    - Top 5 applications with the highest issue frequency:
                        (1) Mobile JKN (BPJS Health) -> Login (3 reviews)
                        (2) MyPertamina -> Bug (3 reviews)
                        (3) OSS Indonesia (Ministry of Investment) -> Bug (3 reviews)
                        (4) JAKI (Jakarta Government App) -> Login (2 reviews)
                        (5) LMS Kemendes -> Login (2 reviews)

                    - Note:
                        + Differences in results stem from timing. Classifications 1-3 were done on Aug 16, 2025, while Classification 4 was run on Aug 17, 2025.
                        - During this gap, 5 new user reviews appeared, causing slight variation in results.  
                            

AI Support Explanation  :

In this capstone project, Artificial Intelligence (AI) serves as the core analytical engine to process and extract insights from public reviews of government-owned mobile applications in Indonesia. A Large Language Model (LLM - IBM Granite) is utilized to conduct comprehensive multi-level analysis through the following functions:

    1. Sentiment Classification:
        Each review is analyzed and categorized into three sentiment types:
            - Positive -> expressing satisfaction, appreciation, and support.- Negative -> containing criticism, complaints, or frustration.
            - Neutral -> providing informative or balanced feedback without strong polarity.
        
        This classification allows for a more nuanced understanding of user perception beyond a simple positive/negative split.
        
    2. Summarization:
        Two summarization approaches are employed:
            - LLM-Based Summarization -> the model generates concise summaries of recurring issues, feature requests, and positive highlights directly from thousands of user reviews.

            - Manual (Self-Evaluation) Summarization -> human-driven validation of sentiment distribution and thematic patterns to ensure reliability, contextual accuracy, and alignment with real user concerns.

    3. Text-Based Insight Extraction:
        Beyond sentiment, the LLM identifies patterns, frequent keywords, and thematic clusters. The key recurring themes include:
        
            - Performance & Stability -> frequent issues with bugs, crashes, and slow response.
            - Accessibility & Usability -> login failures, password reset difficulties, and non-intuitive navigation.
            - Benefits & Positive Impact -> recognition that the apps improve access to public services.
            - Security & Public Trust -> some concerns raised regarding data privacy and system security.
            
    4. Multi-Level Classification & Summarization Process
        To ensure comprehensive insights, sentiment classification and summarization were conducted across four levels of analysis:
            - Sentiment Classification per Review -> analyzing each review individually.
            - Sentiment Classification per Review per Application -> mapping sentiment distribution per app, performed through both automation and manual evaluation for selected apps.
            - Sentiment Classification per Review per APK Label -> categorizing reviews based on specific labels (e.g., login, error, bug, security) to highlight recurring technical or functional issues.
            - Sentiment Classification per Review per Application per APK Label -> a multilabel / cross-classification approach combining both application and technical labels, enabling deeper insights (e.g., identifying which apps most frequently face login issues or receive positive feedback on certain features).

Conclusion and Recommendation   :

Conclusion according to analytical result, findings and insights :

    1. Negative Sentiment Dominates -> Nearly half of reviews highlight dissatisfaction (login failures, crashes, slow performance).
    2. Positive Sentiment Exists -> Users recognize the benefits and potential of digital apps for easier access to public services.
    3. Critical Weak Points -> Authentication (login/OTP), stability (bugs, crashes), and poor UX are the most common pain points.
    4. Polarization Across Apps -> Some apps (e.g., Pegadaian Digital, SIMPKB, JDIH Kemensos) maintain positive sentiment, while core service apps (Digital ID, SiCantik Cloud, Satudikti) suffer heavy criticism.
    5. Trust vs. Frustration -> Despite technical issues, users still expect government apps to work better -> showing strong demand and reliance on digital public services.
    6. Public Service Gap -> Apps often fail to meet the practical needs of citizens due to lack of usability, integration, and reliability.
    7. Security Concerns -> Growing fears of data breaches and privacy risks highlight the urgent need for robust cybersecurity measures.


Recommendations :

    a. For Government & Policymakers
        - Prioritize Critical Fixes -> Allocate resources to fix login/authentication modules and core service app stability.
        - Periodic Monitoring -> Establish continuous AI-powered review monitoring for early detection of recurring issues.
        - Budget Optimization -> Consolidate redundant apps, avoid overlapping functions, and focus spending on high-impact apps.
        - Benchmarking -> Use successful apps (e.g., Pegadaian Digital) as models for best practices in UI/UX and performance.
        - Public Service Needs Assessment -> Conduct thorough requirement analysis before app development to ensure alignment with citizen needs.
        - Cybersecurity Standards -> Mandate strong data protection frameworks to prevent data leaks, identity theft, and misuse of personal information.
        - Quality Assurance (QA) Testing -> Implement mandatory testing protocols (functional, performance, and security testing) before deployment.
        - App Rationalization & Integration :
            + Avoid creating too many fragmented apps that confuse users and lack adoption.
            + Develop a "One-for-All Mobile App System" that integrates multiple public services into a single, user-friendly platform.
            + This reduces redundancy, saves costs, and improves user engagement by centralizing essential services in one secure ecosystem.

    b. For Developers & Vendors :
        - Quick Wins -> Address urgent issues: login, crash handling, server reliability.
        - Stronger QA & Testing -> Implement rigorous pre-launch and post-update testing.
        - User-Centric Development -> Incorporate user feedback into feature updates and UX redesign.
        - Support Systems -> Provide clear error messages, FAQs, and integrated helpdesk/chatbots.
        - Security-by-Design -> Embed cybersecurity principles in app architecture, including encryption, secure authentication, and penetration testing.
        - QA-Driven Development -> Strengthen Quality Assurance & automated testing pipelines to minimize crashes and bugs.
        - User-Centered Updates -> Regularly update apps based on user feedback and evolving service requirements.
        - Incident Response -> Establish monitoring and quick-response systems for security incidents and technical failures.

    c. For Stakeholders (Public & Agencies) :
        - Transparency & Accountability -> Share progress on app improvements, bug fixes, and security measures.
        - Data Privacy Awareness -> Educate users on how their data is protected and give them control over personal information.
        - Cross-Agency Collaboration -> Improve integration between apps to reduce fragmentation and provide seamless digital public services.

        Especially for public:
        - Active Participation -> Continue providing feedback, suggestions, and constructive criticism to help improve government mobile applications.
        - Digital Ecosystem Building -> Contribute to shaping a healthier digital public service ecosystem in Indonesia through active engagement.
        - Openness to Technology -> Avoid resistance or indifference toward technological progress; embrace the use of mobile applications as tools for easier access to services.
        - Responsible Usage -> Use apps wisely while being aware of digital literacy and data privacy practices.


Note            : 

Attached in this presentation are the classification results of 100 reviews per application, focusing on several government-owned mobile apps that recorded the highest number of negative review sentiments. This provides a clear picture of the most critical pain points directly voiced by users.


Closing         :

On this historic moment of Indonesia's 80th Independence Day, let us celebrate with the spirit of innovation and digitalization that truly empowers the people.

As a special gift from this Insight & Findings Project, I present actionable recommendations for the Government of Indonesia to enhance public service quality, strengthen data security, and foster a more efficient, inclusive, and impactful mobile app ecosystem for all citizens.

**Happy 80th Independence Day, Republic of Indonesia. Together with technology, let's achieve true digital freedom for everyone**




================================================================================================================================================================



Judul Proyek        : **"Analisis dan Klasifikasi Sentimen Ulasan Aplikasi Mobile Pemerintah Indonesia Berbasis AI untuk Peningkatan Layanan Publik"**

Penjelasan Proyek   : 

Transformasi digital yang terjadi secara global dalam dua dekade terakhir telah membawa perubahan signifikan pada cara masyarakat mengakses informasi, berinteraksi, dan memperoleh layanan publik. Fenomena ini juga terjadi di Indonesia, di mana pemerintah berupaya mengadopsi teknologi digital untuk meningkatkan efisiensi dan transparansi pelayanan. Namun, pesatnya digitalisasi ini juga memunculkan tantangan besar. Berdasarkan data Kementerian PAN-RB, terdapat lebih dari 27.000 aplikasi milik pemerintah yang dikelola berbagai kementerian, lembaga, dan pemerintah daerah. Setiap tahun, anggaran besar dikeluarkan untuk pemeliharaan aplikasi-aplikasi ini, namun tidak semua dimanfaatkan secara optimal (Idris, 2023). Banyak di antaranya memiliki fungsi yang tumpang tindih, antarmuka yang sulit digunakan, hingga server yang jarang diakses publik (Yanwardhana, 2024). Kondisi ini tidak hanya mengakibatkan pemborosan anggaran negara, tetapi juga membuka celah terjadinya inefisiensi struktural dan potensi penyalahgunaan dana. Dalam beberapa kasus, pengadaan atau pengembangan aplikasi yang tidak relevan atau tidak berfungsi maksimal dapat menjadi pintu masuk praktik mark-up biaya, pengadaan fiktif, maupun kolusi dengan pihak vendor, yang pada akhirnya merugikan keuangan negara dan menghambat kualitas pelayanan publik.

Proyek ini hadir untuk memberikan kontribusi pada perbaikan kualitas layanan publik digital melalui pendekatan AI-powered sentiment classification dan insight analysis. Tujuan utamanya adalah mengevaluasi secara sistematis ulasan dan umpan balik masyarakat terhadap aplikasi-aplikasi mobile pemerintah Indonesia. Data akan dikumpulkan dari sumber publik yang legal dan terbuka yakni Google Play Store. Selanjutnya, teknik Natural Language Processing (NLP) akan digunakan, termasuk penerapan Large Language Models (LLMs) menggunakan IBM Granite Model, untuk mengklasifikasikan ulasan menjadi kategori sentimen positif, netral, dan negatif. Lebih jauh, analisis insight extraction akan mengidentifikasi isu utama, keluhan pengguna, serta saran-saran yang sering muncul. Pendekatan ini memastikan bahwa setiap opini masyarakat dapat diubah menjadi informasi strategis yang terukur dan relevan.

Hasil akhir proyek ini diharapkan dapat memberikan wawasan berbasis data yang akurat dan mudah dipahami bagi para pemangku kepentingan, mulai dari pengembang aplikasi hingga pembuat kebijakan. Dengan informasi tersebut, mereka dapat mengidentifikasi kesenjangan layanan yang paling mendesak untuk diperbaiki, memprioritaskan pengembangan fitur yang paling dibutuhkan, serta merumuskan strategi perbaikan yang terarah dan dapat diimplementasikan secara nyata. Dalam jangka panjang, inisiatif ini diharapkan mampu meningkatkan kepercayaan publik terhadap layanan digital pemerintah, mengoptimalkan pemanfaatan anggaran teknologi, dan mendorong terciptanya ekosistem aplikasi pemerintah yang efisien, terintegrasi, dan benar-benar bermanfaat bagi masyarakat luas. Dengan kata lain, proyek ini bukan hanya sekadar analisis data, tetapi menjadi langkah konkret menuju transformasi digital pemerintah yang lebih responsif dan berorientasi pada kebutuhan pengguna.

Daftar Pustaka      :

Idris, Muhammad. (2023, Maret). Pemborosan Anggaran, Ada 27.000 Aplikasi Milik Pemerintah Lewat Vendor. https://money.kompas.com/read/2023/03/20/193607826/pemborosan-anggaran-ada-27000-aplikasi-milik-pemerintah-lewat-vendor.

Yanwardhana, Emir. (2024, Mei). Jokowi Kecewa Pusat & Daerah Habiskan Rp6,2 T Buat Bikin Aplikasi. https://www.cnbcindonesia.com/news/20240527151234-4-541502/jokowi-kecewa-pusat-daerah-habiskan-rp62-t-buat-bikin-aplikasi?


Link Dataset Mentah :

        Format url mengambil data review app from Google Play with Library google_play_scraper (Python) :

        https://play.google.com/store/apps/details?id=<package_name>
         
        Link Dataset Aplikasi Mobile Pemerintah Indonesia pada Google Play Store :

        1. SATUSEHAT - PeduliLindungi --> https://play.google.com/store/apps/details?id=com.telkom.tracencare
        2. JAKI - Jakarta Kini --> https://play.google.com/store/apps/details?id=id.go.jakarta.smartcity.jaki
        3. Identitas Kependudukan Digital --> https://play.google.com/store/apps/details?id=gov.dukcapil.mobile_id
        4. M-Paspor --> https://play.google.com/store/apps/details?id=id.go.imigrasi.paspor_online
        5. Jamsostek Mobile - BPJSTKU --> https://play.google.com/store/apps/details?id=com.bpjstku
        6. MySAPK BKN --> https://play.google.com/store/apps/details?id=com.nudi.bkn.sapk
        7. SiCantik Cloud --> https://play.google.com/store/apps/details?id=id.go.perizinan.sicantikcloud
        8. Mobile JKN --> https://play.google.com/store/apps/details?id=app.bpjs.mobile
        9. Cek Bansos --> https://play.google.com/store/apps/details?id=id.go.kemensos.pelaporan
        10. PLN Mobile --> https://play.google.com/store/apps/details?id=com.icon.pln123
        11. MyPertamina --> https://play.google.com/store/apps/details?id=com.dafturn.mypertamina
        12. Pegadaian Digital --> https://play.google.com/store/apps/details?id=com.pegadaiandigital
        13. Digital Korlantas POLRI --> https://play.google.com/store/apps/details?id=id.qoin.korlantas.user
        14. SIGNAL - Samsat Digital Nasional --> https://play.google.com/store/apps/details?id=app.signal.id
        15. POLRI PRESISI --> https://play.google.com/store/apps/details?id=superapps.polri.presisi.presisi
        16. Mobile JKN Faskes - BPJS Kesehatan --> https://play.google.com/store/apps/details?id=app.bpjs.mobilefaskes
        17. OSS Indonesia --> https://play.google.com/store/apps/details?id=id.go.oss
        18. Info BMKG --> https://play.google.com/store/apps/details?id=com.Info_BMKG
        19. Sentuh Tanahku --> https://play.google.com/store/apps/details?id=id.go.bpn.sentuh
        20. JDIH Kemensos --> https://play.google.com/store/apps/details?id=id.go.kemensos.jdih.jdih_kemensos_f
        21. LMS Kemendes --> https://play.google.com/store/apps/details?id=com.mid.lmskemendes
        22. Internal POLRI --> https://play.google.com/store/apps/details?id=superapps.polri.internal.presisi
        23. Pemutakhiran PK - BKKBN --> https://play.google.com/store/apps/details?id=com.yosicsa.pemutakhiranpk
        24. SIKS Mobile --> https://play.google.com/store/apps/details?id=id.go.kemensos.sagismobile
        25. M-Pajak --> https://play.google.com/store/apps/details?id=id.go.pajak.djp
        26. iPusnas --> https://play.google.com/store/apps/details?id=mam.reader.ipusnas
        27. SIMPKB --> https://play.google.com/store/apps/details?id=id.simpkb.app
        28. Jaga - KPK --> https://play.google.com/store/apps/details?id=id.or.checkmy
        29. Satudikti - Kemdikbud --> https://play.google.com/store/apps/details?id=id.satudikti.app
        30. IDENTIK PKH Kementan - Peruri --> https://play.google.com/store/apps/details?id=com.solusibejo.hiternak
        31. BPKH Apps --> https://play.google.com/store/apps/details?id=id.go.bpkh.nmva
        32. AK23 Online by Pusinafis POLRI --> https://play.google.com/store/apps/details?id=com.ak23.online
        33. GTK Kemenag --> https://play.google.com/store/apps/details?id=id.siap.ptk

Insight and Findings:

        Alur Proses Pengerjaan:
        
        1. Pada proses klasifikasi review aplikasi mobile di bawah Pemerintah Indonesia kali ini, sebaran data review yang di scrap, sebagai berikut :
            - Mengambil review dari semua aplikasi maka jumlah review untuk setiap aplikasi akan sama (misal: 5 review * 33 app = 165 total review)
            - Mengambil review target aplikasi tertentu untuk diklasifikasi 100 review terbaru dalam menentukan kecendrungan sentimen terhadap aplikasi tersebut
            - 
        2. Selanjutnya dilakukan data preprocessing untuk menghindari bias data, terutama pada review yang berulang (duplicate review).
        3. Dalam melakukan klasifikasi menggunakan IBM Granite Model dibagi/slicing dataset ke dalam bebarapa batch (1 batch = 100 data review)
        4. Klasifikasi dan Summarization dilakukan sebanyak 4 kali yakni:
            - Klasifikasi Sentimen per Review
            - Klasifikasi Sentimen per Review per Aplikasi (Automation dan Manual, khusus aplikasi tertentu)
            - Klasifikasi Sentimen per Review per Label APK
            - Klasifikasi Sentimen per Review per Aplikasi per Label APK (Multilabel classify/cross classify)
        

        Hasil Temuan dan Analisis Insight:
            1. Klasifikasi Sentimen per Review:
                - Distribusi Hasil:
                    a. Jumlah Review dengan Sentimen Positive = 62 (37,35%)
                    b. Jumlah Review dengan Sentimen Negative = 78 (46,99%)
                    c. Jumlah Review dengan Sentimen Neutral = 26 (15,66%)
                - Temuan umum :
                    a. Mayoritas review menunjukkan sentimen negatif, yang mendominasi hampir setengah dari total umpan balik. Keluhan umumnya terkait error, lemot, crash, kesulitan login, atau aplikasi tiba-tiba berhenti.
                    
                    b. Review positif tetap signifikan (lebih dari sepertiga total review), dengan kata kunci yang menonjol seperti "bagus", "mudah digunakan", dan "membantu". Ini menunjukkan aplikasi pemerintah sudah memberikan manfaat nyata bagi sebagian besar pengguna.

                    c. Review netral relatif sedikit. Umumnya berupa kombinasi pujian disertai saran, misalnya "aplikasi sudah bagus, tapi tolong perbaiki fitur upload file".
                
                - Insight :
            
                    a. Dominasi Sentimen Review Negatif:
                        Rasio review negatif : positif = 1,25 : 1. Ini berarti masih ada peluang besar untuk mengubah persepsi publik, jika isu teknis segera diperbaiki.

                    b. Ekspektasi Tinggi: 
                        Rendahnya jumlah review netral (15,6%) menunjukkan pengguna cenderung ekstrem dalam memberikan penilaian -> sangat puas (positif) atau sangat kecewa (negatif). Hal ini mencerminkan ekspektasi tinggi masyarakat terhadap aplikasi pemerintah.

                    c. Pola Sentimen (evaluasi manual):
                        - Review Positif dipicu oleh kemanfaatan aplikasi (akses layanan lebih cepat dan praktis/simple).
                        - Review Negatif didorong oleh pengalaman buruk pada fungsi inti fitur aplikasi (bug, crash, login).
                        - Review Netral muncul saat apresiasi bercampur dengan keluhan/saran.

                - Implikasi dan Rekomendasi:
                        a. Quick Wins: Fokus pada perbaikan bug, login, dan stabilitas aplikasi dapat langsung menurunkan jumlah review negatif.
                        b. Strategi Jangka Panjang:
                            + Edukasi dan sosialisasi fitur kepada pengguna agar mereka lebih memahami manfaat aplikasi.
                            + Pengembangan fitur tambahan sesuai permintaan (misalnya akses informasi lebih cepat, peningkatan mutu UI/UX) untuk mengubah tren review netral menjadi positif.
                            + Menjaga konsistensi kualitas akan memperkuat persepsi publik terhadap brand aplikasi pemerintah.

            2. Klasifikasi Sentimen per Review per Aplikasi:
                - Distribusi Hasil:
                    a. Jumlah Review dengan Sentimen Positive = 61 (36,53%)
                    b. Jumlah Review dengan Sentimen Negative = 80 (47,90%)
                    c. Jumlah Review dengan Sentimen Neutral = 26 (15,57%)

                    Note : Terdapat kekeliruan (inaccuracy) pada output model berdasarkan hasil prompt sehingga total jumlah sentimen sebanyak 167 (kelebihan 2 review pada output model). Namun hal ini tidak berdampak signifikan terhadap sebaran hasil klasifikasi review. 

                - Temuan umum :

                    a. Mayoritas aplikasi pemerintah memiliki komposisi review negatif yang cukup tinggi, terutama pada aplikasi layanan inti (misalnya identitas, kesehatan, pendidikan).
                    
                    b. Beberapa aplikasi masih mampu menyeimbangkan sentimen positif, terutama aplikasi yang dianggap praktis, informatif, dan bermanfaat langsung bagi masyarakat.

                    c. Aplikasi dengan Sentimen Positif Dominan :
                        + "Pegadaian Digital", "SIMPKB", dan "JDIH Kemensos" memperoleh skor sentimen tertinggi (skor +4 sampai +5).
                        + Review positif didominasi oleh komentar seperti "mudah digunakan", "bermanfaat", dan "informasi jelas", "bagus", "ok".
                    
                    d. Aplikasi dengan Sentimen Negatif Dominan
                        + Berdasarkan ranking skor sentimen (Positif - Negatif), 5 aplikasi dengan performa sentimen terburuk :
                        Identitas Kependudukan Digital (IKD) -> Skor -5
                        Pemutakhiran PK - BKKBN -> Skor -5
                        Satudikti - Kemendikbud -> Skor -5
                        SiCantik Cloud -> Skor -5
                        Jamsostek Mobile - BPJSTKU -> Skor -4
                        
                        Note : skor dihitung dari hasil pengurangan jumlah review sentimen positive - jumlah review sentimen Negative

                        + "Identitas Kependudukan Digital (IKD)", "Pemutakhiran PK - BKKBN", "Satudikti - Kemendikbud", "SiCantik Cloud - Komdigi", dan "Jamsostek Mobile BPJSTKU" memperoleh skor sentimen terendah (skor -5 sampai -4).
                        
                        + Keluhan utama berkisar pada bug teknis, kesulitan login, aplikasi sering crash, dan performa lambat.
                        
                        + Aplikasi SiCANTIK Cloud merupakan singkatan dari Aplikasi Cerdas Layanan Perizinan Terpadu untuk Publik berupa sistem cloud yang disediakan oleh Kementerian Komunikasi dan Informatika yang dapat digunakan oleh instansi pemerintah baik pemerintah pusat maupun pemerintah daerah.
                        Meskipun berada di bawah Kementerian Kominfo/Komdigi, aplikasi SiCANTIK Cloud justru didominasi review negatif. Hal ini menunjukkan bahwa status kelembagaan tidak otomatis menjamin kualitas layanan digital. Keluhan utama berupa login gagal, proses lama, hingga error teknis berulang mencerminkan ironi: aplikasi yang seharusnya menjadi role model transformasi digital pemerintah malah memperlihatkan jurang antara visi besar digitalisasi dan realita implementasi di lapangan.
                
                - Insight :
            
                    a. Polaritas Tinggi antar Aplikasi
                        Terlihat jelas aplikasi terbagi dua kutub:
                        + Kelompok aplikasi dengan review positif tinggi (Pegadaian Digital, SIMPKB, JDIH Kemensos, dsb).+ Kelompok aplikasi dengan review negatif dominan (IKD, Pemutakhiran PK-BKKBN, Satudikti, dsb).
                        
                        Hal ini menandakan kualitas dan pengalaman pengguna aplikasi pemerintah masih sangat bervariasi.

                    b. Aplikasi Identitas dan Pendidikan = Titik Lemah 
                        + Aplikasi dengan fungsi fundamental (identitas, data kependudukan, pendidikan, layanan dasar) justru menjadi yang paling banyak menerima keluhan.
                        + Menunjukkan bahwa isu teknis di layanan inti sangat krusial karena langsung berdampak luas ke masyarakat.

                    c. Pola Keluhan secara Umum:
                        + Login dan Autentikasi Gagal: banyak pengguna tidak bisa masuk walaupun data sudah benar.
                        + Crash dan Lemot: aplikasi sering keluar sendiri, terutama pada HP menengah ke bawah.
                        + User Experience Buruk: navigasi membingungkan, fitur utama tidak berjalan mulus.
                        + Ekspektasi Tinggi -> Kekecewaan Besar: karena aplikasi ini terkait layanan vital (KTP Digital, pendidikan, BPJS, dll), kekecewaan pengguna langsung berujung review negatif.

                - Implikasi dan Rekomendasi:
                        a. Validasi Temuan dengan Data Baru :
                            + Untuk memastikan akurasi khusus pada 5 aplikasi dengan skor tren negative terbanyak (sangat buruk), perlu dilakukan pengambilan tambahan 50 review terbaru per aplikasi tersebut (5 aplikasi x 50 = 250 review total).

                            + Tujuan: menguji konsistensi pola keluhan (apakah memang masih dominan negatif atau ada tren perbaikan).

                        b. Quick Wins :
                            + Fokus perbaikan bug teknis dan login pada 5 aplikasi terburuk bisa langsung menurunkan jumlah review negatif.
                            
                            + Tindaklanjuti review netral dengan roadmap fitur agar aspirasi pengguna tetap diakomodasi.
                            
                            + Prioritaskan perbaikan teknis pada aspek yang paling sering muncul dalam review negatif (bug, performa, crash).

                            + Benchmarking ke aplikasi dengan skor positif (Pegadaian Digital, SIMPKB) untuk melihat perbedaan strategi UX dan performa.

                        c. Strategi Jangka Panjang
                            + Lakukan monitoring sentimen periodik untuk mengukur efek update/perbaikan setiap fitur.

                            + Melakukan proses testing melalui sarana manajemen quality product assurance yang ketat dan berjenjang sebelum di deploy/publish.

            
            3. Klasifikasi Sentimen per Review per Label:
                - Distribusi Hasil:
                    a. Jumlah Review dengan Sentimen Positive = 71 (43,03%)
                    b. Jumlah Review dengan Sentimen Negative = 87 (52,73%)
                    c. Jumlah Review dengan Sentimen Neutral = 26 7 (4,24%)

                - Temuan umum :

                    a. Sentimen negatif masih mendominasi (lebih dari separuh review), dengan keluhan (label APK) terbanyak terkait login gagal, error umum, dan lupa sandi/forgot password.
                    b. Review positif tetap kuat (43%), menekankan manfaat aplikasi meskipun ada banyak isu teknis.
                    c. Review netral relatif sedikit (4%), biasanya berupa apresiasi sekaligus saran perbaikan.
                    d. Masalah Berulang :
                        + Kendala Login mendominasi (17 review / 10,3%).+ Error umum dan lupa password cukup sering muncul (masing-masing 4 review).
                        + Masalah lain (bug, crash, server down, OTP, kinerja lambat, pembayaran) muncul tapi dengan frekuensi rendah (1-2 review).
                    e. Permintaan Fitur: Tidak ada permintaan fitur eksplisit yang konsisten.
                    f. Positive Highlights:
                        + Aplikasi dianggap bermanfaat dan memudahkan urusan administrasi.
                        + Tampilan dan aksesibilitas cukup baik menurut sebagian pengguna.
                        + Ada persepsi positif mendukung/support terhadap niat pemerintah digitalisasi layanan.
                    g. Negative Highlights:
                        + Login dan otentikasi (OTP, password) sering gagal, menjadi penghalang utama akses.
                        + Error umum, bug, server down, dan crash memperburuk pengalaman user.
                        + Keamanan data dan pembayaran juga sempat dikeluhkan walau kecil (1-2 review).

                - Insight :
            
                    a. Dominasi Sentimen Negatif
                    Rasio review negatif : positif = 1,22 : 1 -> menandakan pengalaman teknis buruk lebih berpengaruh dibandingkan manfaat aplikasi.
                    b. Ekspektasi Tinggi
                    Rendahnya porsi review netral menunjukkan masyarakat memberi penilaian ekstrem: sangat puas atau sangat kecewa.
                    c. Pola Sentimen:
                    + Positif: Aplikasi dianggap membantu, praktis, dan bermanfaat.
                    + Negatif: Terkait fungsi inti aplikasi (login, password, bug, crash, server down, OTP).
                    + Netral: Apresiasi + saran, misalnya "sudah bagus tapi tolong perbaiki fitur login/upload".
                    d. Login sebagai Pain Point Utama (Main Fitur): Dari seluruh isu teknis, lebih dari 10% review mengeluhkan masalah login, menjadikannya hambatan kritis akses awal pada aplikasi. Artinya, fungsi inti aplikasi belum kokoh dan merusak persepsi keseluruhan pengalaman user.
                    e. Korelasi Sentimen dengan Fungsi Inti (Main Fitur): Review negatif hampir selalu terkait fungsi dasar (login, OTP, password reset, stabilitas server). Hal ini menunjukkan bahwa user menilai aplikasi berdasarkan reliability fitur inti lebih daripada fitur tambahan atau tampilan.
                    f. Trust vs. Frustrasi (Emosi User): 
                    Walaupun ada frustrasi tinggi, masih banyak user yang mendukung tujuan digitalisasi pemerintah. Ini menandakan adanya trust capital yang harus segera dijaga dengan peningkatan kualitas teknis.

                - Implikasi dan Rekomendasi:
                        a. Quick Wins:
                            + Stabilisasi Login dan Otentikasi: perbaiki modul login, reset password, dan OTP sebagai prioritas.
                            + Error Handling: tampilkan pesan error yang jelas dan solutif (misalnya "server sedang sibuk, coba 5 menit lagi"), bukan hanya "error".
                            + Penguatan QA: lakukan stress testing dan regression test berlapis sebelum update dipublish.

                        b. Strategi jangka panjang:
                            + Server Reliability: optimalkan kapasitas server dan load balancing agar crash dan downtime berkurang.
                            + Security Assurance: perkuat sistem keamanan, terutama terkait data pribadi dan transaksi pembayaran (karena sudah ada kekhawatiran meski kecil).
                            + User Support: sediakan kanal bantuan cepat (chatbot, FAQ interaktif, helpdesk 24/7) untuk masalah login/OTP.
                            
            4. Klasifikasi Sentimen per Review per Label per Aplikasi:
                a. Hasil Insight and result sesuai dengan kombinasi hasil Klasifikasi ke-2 dan ke-3.
                b. Terdapat differentiation result pada Jumlah Label APK (Issue/Problem) terhadap Aplikasi, dimana list 5 Aplikasi dengan Label APK (Issue/Problem) tertinggi -> terendah:
                    - Mobile JKN Faskes-BPJS Kesehatan - Issue: Login sebanyak 3 review
                    - MyPertamina - Issue: Bug sebanyak 3 review
                    - OSS Indonesia-Kementrian Investasi - Issue: Bug sebanyak 3 review
                    - JAKI-Jakarta Kini - Issue: Login sebanyak 2 review
                    - LMS Kemendes - Issue: Login sebanyak 2 review

                Catatan: Perbedaan hasil ini terjadi karena adanya selisih waktu pengambilan data. Proses klasifikasi ke-1 hingga ke-3 dilakukan pada tanggal 16 Agustus 2025, sedangkan klasifikasi ke-4 dilakukan pada tanggal 17 Agustus 2025. Dalam rentang waktu tersebut terdapat 5 review terbaru yang masuk dari pengguna aplikasi, sehingga menyebabkan adanya perbedaan pada data hasil klasifikasi.  
                            
Penutup     :

Di momentum bersejarah 80 Tahun Kemerdekaan Indonesia, mari rayakan dengan semangat inovasi dan digitalisasi yang semakin memerdekakan rakyat.

Sebagai hadiah dari Insight & Findings Project ini, saya Azarya Kairossutan Sacri Pusaka Dami persembahkan rekomendasi nyata bagi Pemerintah Indonesia untuk meningkatkan kualitas layanan publik, memperkuat keamanan data, serta mendorong ekosistem aplikasi yang lebih efisien, inklusif, dan bermanfaat bagi seluruh masyarakat.

Dirgahayu ke-80 Republik Indonesia. Bersama teknologi, kita wujudkan kemerdekaan digital untuk semua.
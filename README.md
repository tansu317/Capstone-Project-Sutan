"# Capstone-Project-Sutan" 

Email                   : sutandami@gmail.com

Title Project           : "AI-Powered Sentiment Classification and Insight Analysis of Indonesian Government Mobile Apps Reviews for Public Service Improvement"

Project Overview        :

The global digital transformation over the past two decades has significantly changed the way people access information, interact, and obtain public services. This phenomenon has also occurred in Indonesia, where the government strives to adopt digital technologies to improve service efficiency and transparency. However, the rapid pace of digitalization has also created major challenges. According to data from the Ministry of State Apparatus Utilization and Bureaucratic Reform (KemenPAN-RB), there are more than 27,000 government-owned applications managed by various ministries, agencies, and local governments. Each year, a large budget is allocated to maintain these applications, yet not all are utilized optimally (Idris, 2023). Many of them have overlapping functions, poor user interfaces, or servers that are rarely accessed by the public (Yanwardhana, 2024). This situation not only leads to wasteful public spending but also opens opportunities for structural inefficiencies and potential misuse of funds. In some cases, the procurement or development of irrelevant or underperforming applications can pave the way for cost mark-ups, fictitious projects, or collusion with vendors, ultimately harming state finances and hindering the quality of public services.

This project aims to contribute to improving the quality of digital public services through an AI-powered sentiment classification and insight analysis approach. The main goal is to systematically evaluate user reviews and feedback on Indonesian government mobile applications. Data will be collected from legal and publicly available sources such as Google Play Store and Apple App Store. Next, Natural Language Processing (NLP) techniques will be applied, including the use of Large Language Models (LLMs) with the IBM Granite Model, to classify reviews into positive, neutral, and negative sentiment categories. Furthermore, insight extraction analysis will identify key issues, user complaints, and recurring suggestions. This approach ensures that every citizen's opinion can be transformed into measurable and relevant strategic information.

The outcome of this project is expected to provide accurate, data-driven insights that are easy to understand for stakeholders from application developers to policymakers. With this information, they can identify the most urgent service gaps to address, prioritize the development of the most needed features, and formulate well-directed, actionable improvement strategies. In the long term, this initiative aims to increase public trust in government digital services, optimize the use of technology budgets, and promote the creation of an efficient, integrated, and truly beneficial government application ecosystem for the wider community. In other words, this project is not merely about data analysis it is a concrete step towards a more responsive, user-centered digital government transformation.

References              :

Idris, Muhammad. (2023, March). Pemborosan Anggaran, Ada 27.000 Aplikasi Milik Pemerintah Lewat Vendor. https://money.kompas.com/read/2023/03/20/193607826/pemborosan-anggaran-ada-27000-aplikasi-milik-pemerintah-lewat-vendor.

Yanwardhana, Emir. (2024, May). Jokowi Kecewa Pusat & Daerah Habiskan Rp6,2 T Buat Bikin Aplikasi. https://www.cnbcindonesia.com/news/20240527151234-4-541502/jokowi-kecewa-pusat-daerah-habiskan-rp62-t-buat-bikin-aplikasi?


Raw Dataset Link        :

        Format link get data review app from Google Play with Library google_play_scraper (Python) :

        https://play.google.com/store/apps/details?id=<package_name>
         
        Google Play Store Links Dataset for Gov Indonesian Mobile Apps :

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

        
        Format link get data review app from App Store with Library app_store_scrapr (Python) :

        https://apps.apple.com/id/app/<app-name>/id<app_id>

        App Store Links Dataset for Gov Indonesian Mobile Apps :
        (ID DATASET LINK APPSTORE MASIH BELUM BENAR HARUS DI CEK LAGI)
        1. SATUSEHAT - PeduliLindungi --> https://apps.apple.com/id/app/satusehat-mobile/id1504600374
        2. JAKI - Jakarta Kini --> https://apps.apple.com/id/app/jaki-jakarta-kini/id1481694314
        3. Identitas Kependudukan Digital --> https://apps.apple.com/id/app/identitas-kependudukan-digital/id1624421463
        4. M-Paspor --> https://apps.apple.com/id/app/m-paspor/id1585484533
        5. Jamsostek Mobile - BPJSTKU --> https://apps.apple.com/id/app/jmo-jamsostek-mobile/id1482867497


Analysis Process        :

        1. Data Collection      :
            - Identify a list of Indonesian government mobile applications across various ministries and sectors.
            - Retrieve publicly available user reviews from Google Play Store and Apple App Store using scraping libraries (google-play-scraper, app_store_scrapr).
            - Gather review metadata including:
                + App name & package ID
                + Username
                + Rating score
                + Review text
                + Review date & app version

        2. Data Preprocessing   :
            - Remove duplicate entries and filter non-Indonesian language reviews.
            - Normalize text by lowercasing, removing punctuation, special characters, and stopwords.
            - Tokenize and clean review content for NLP processing.
            - Structure data into a pandas DataFrame for analysis.

        3. AI-Powered Analysis  :
            - Sentiment Classification:
                Use a Large Language Model (LLM) by IBM Granite model to classify reviews into Positive, Neutral, or Negative
            - Insight Extraction:
                Apply summarization models to extract key issues, recurring suggestions, and positive highlights from user feedback.
            - Quantitative Analysis:
                + Calculate sentiment distribution per app.
                + Identify top recurring keywords and topics using NLP techniques (e.g., TF-IDF, keyword extraction).

        4. Insight and Findings : 
            analytical result, logical explanation, and unique.

        5. Conclusion and Recommendation    :
            Recommendation for Indonesian Government, developer vendors, and other stakeholders to enhance public service quality in digital technologies Mobile Apss.

Insight and Findings    :


AI Support Explanation  :








================================================================================================================================================================


Judul Proyek        : "Analisis dan Klasifikasi Sentimen Ulasan Aplikasi Mobile Pemerintah Indonesia Berbasis AI untuk Peningkatan Layanan Publik"

Penjelasan Proyek   : 

Transformasi digital yang terjadi secara global dalam dua dekade terakhir telah membawa perubahan signifikan pada cara masyarakat mengakses informasi, berinteraksi, dan memperoleh layanan publik. Fenomena ini juga terjadi di Indonesia, di mana pemerintah berupaya mengadopsi teknologi digital untuk meningkatkan efisiensi dan transparansi pelayanan. Namun, pesatnya digitalisasi ini juga memunculkan tantangan besar. Berdasarkan data Kementerian PAN-RB, terdapat lebih dari 27.000 aplikasi milik pemerintah yang dikelola berbagai kementerian, lembaga, dan pemerintah daerah. Setiap tahun, anggaran besar dikeluarkan untuk pemeliharaan aplikasi-aplikasi ini, namun tidak semua dimanfaatkan secara optimal (Idris, 2023). Banyak di antaranya memiliki fungsi yang tumpang tindih, antarmuka yang sulit digunakan, hingga server yang jarang diakses publik (Yanwardhana, 2024). Kondisi ini tidak hanya mengakibatkan pemborosan anggaran negara, tetapi juga membuka celah terjadinya inefisiensi struktural dan potensi penyalahgunaan dana. Dalam beberapa kasus, pengadaan atau pengembangan aplikasi yang tidak relevan atau tidak berfungsi maksimal dapat menjadi pintu masuk praktik mark-up biaya, pengadaan fiktif, maupun kolusi dengan pihak vendor, yang pada akhirnya merugikan keuangan negara dan menghambat kualitas pelayanan publik.

Proyek ini hadir untuk memberikan kontribusi pada perbaikan kualitas layanan publik digital melalui pendekatan AI-powered sentiment classification dan insight analysis. Tujuan utamanya adalah mengevaluasi secara sistematis ulasan dan umpan balik masyarakat terhadap aplikasi-aplikasi mobile pemerintah Indonesia. Data akan dikumpulkan dari sumber publik yang legal dan terbuka seperti Google Play Store dan Apple App Store. Selanjutnya, teknik Natural Language Processing (NLP) akan digunakan, termasuk penerapan Large Language Models (LLMs) menggunakan IBM Granite Model, untuk mengklasifikasikan ulasan menjadi kategori sentimen positif, netral, dan negatif. Lebih jauh, analisis insight extraction akan mengidentifikasi isu utama, keluhan pengguna, serta saran-saran yang sering muncul. Pendekatan ini memastikan bahwa setiap opini masyarakat dapat diubah menjadi informasi strategis yang terukur dan relevan.

Hasil akhir proyek ini diharapkan dapat memberikan wawasan berbasis data yang akurat dan mudah dipahami bagi para pemangku kepentingan, mulai dari pengembang aplikasi hingga pembuat kebijakan. Dengan informasi tersebut, mereka dapat mengidentifikasi kesenjangan layanan yang paling mendesak untuk diperbaiki, memprioritaskan pengembangan fitur yang paling dibutuhkan, serta merumuskan strategi perbaikan yang terarah dan dapat diimplementasikan secara nyata. Dalam jangka panjang, inisiatif ini diharapkan mampu meningkatkan kepercayaan publik terhadap layanan digital pemerintah, mengoptimalkan pemanfaatan anggaran teknologi, dan mendorong terciptanya ekosistem aplikasi pemerintah yang efisien, terintegrasi, dan benar-benar bermanfaat bagi masyarakat luas. Dengan kata lain, proyek ini bukan hanya sekadar analisis data, tetapi menjadi langkah konkret menuju transformasi digital pemerintah yang lebih responsif dan berorientasi pada kebutuhan pengguna.

Daftar Pustaka      :

Idris, Muhammad. (2023, Maret). Pemborosan Anggaran, Ada 27.000 Aplikasi Milik Pemerintah Lewat Vendor. https://money.kompas.com/read/2023/03/20/193607826/pemborosan-anggaran-ada-27000-aplikasi-milik-pemerintah-lewat-vendor.

Yanwardhana, Emir. (2024, Mei). Jokowi Kecewa Pusat & Daerah Habiskan Rp6,2 T Buat Bikin Aplikasi. https://www.cnbcindonesia.com/news/20240527151234-4-541502/jokowi-kecewa-pusat-daerah-habiskan-rp62-t-buat-bikin-aplikasi?


Link Dataset Mentah :


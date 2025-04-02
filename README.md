# JobRoulette

Building an app to help users quickly apply for jobs in their area

    Tinder-esque swipe to apply jobs
        - filter based on title, location, (remote), employment type, etc. 
        - 


# TO-DO List
    Backend: 
        - Python (Flask), Go (Gin/Echo), NodeJS (Express) 
        - Maybe setup an API to fetch job list based on preference 
            - Flask / Express? 
            Data pipeline
                - scheduled time to scrape new jobs? 
                - 

    Database: 
        - Firebase Firestore? Supabase? 
        - Probably Firebase as its better for mobile apps 
        Caching? 
            - look into Redis

    Authentication
        - Firebase/Supabase Auth? 
        - store user data based on profile
        - job data stored in general database based on region and title, regularly cleaned

    Web Scraping / Job Finder: 
        - Python BS4, Scrapy
        - ZipRecruiter API/Indeed API

    Frontend/Interface: 
        - React Native or Flutter for cross-platform development 
        - look into react-native-deck-swiper or flutter_tindercard 
        State Management: 
            - Redux (React Native) / Provider (Flutter)
            - keep track of which jobs have already been applied for
            - maybe implement an application history / application tracker (whats that one website that does that already, has a chrome extension?) 

    Hosting / Deployment
        - More research on pricing structure of AWS EC2, Heroku, DigitalOcean 
        - Docker for scraping service (easier deployment) 

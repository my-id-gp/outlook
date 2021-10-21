{
    "version": "1.0.0.1",
    "name": "Outlook",
    "description": "Microsoft Outlook is a free app that helps you stay on top of messages, news, and things you need to do. It has SMS, email, alarms & calendar, news, and notes. All of this, with security you can count on.",
    "subtitle": "Personalized. Organized. Connected",
    "theme": "#F3F2F1",
    "display": "Outlook",
    "launch_path": "/index.html",
    "origin": "app://outlook.live.com",
    "cursor": false,
    "icons": {
        "56": "/img/icons/56px.png",
        "84": "/img/icons/84px.png",
        "112": "/img/icons/112px.png",
        "192": "/img/icons/192px.png"
    },
    "developer": {
        "name": "Microsoft",
        "url": "https://www.microsoft.com/"
    },
    "type": "certified",
    "permissions": {
        "sms": {},
        "alarms": {},
        "audio-channel-notification": {},
        "webapps-manage": {},
        "audio-capture": {},
        "speech-recognition": {},
        "device-storage:sdcard": {
            "description": "To access images related to notes from the SD card",
            "access": "readonly"
        },
        "systemXHR": {},
        "serviceworker": {
            "description": "Required for push notifications"
        },
        "desktop-notification": { "description": "Required for push notifications" },
        "push": {
            "description": "Required for push notifications"
        },
        "browser": {},
        "contacts": {
            "access": "readonly",
            "description": "Required for mapping sms numbers to contact details"
        },
        "notifications": {},
        "volumemanager": {}
    },
    "messages": [
        {
            "alarm": "/index.html"
        },
        {
            "sms-received": "/index.html"
        },
        {
            "serviceworker-notification": "/index.html"
        },
        {
            "notification": "/index.html"
        }
    ],
    "chrome": {
        "statusbar": ""
    },
    "redirects": [
        {
            "from": "https://outlook.live.com/owa/auth/dt.aspx",
            "to": "/auth.html"
        },
        {
            "from": "https://outlook.live.com/mail/0",
            "to": "/auth.html"
        },
        {
            "from": "http://www.msn.com/",
            "to": "/auth.html"
        },
        {
            "from": "http://www.bing.com/",
            "to": "/auth.html"
        }
    ],
    "locales": {
        "en-US": {
            "name": "Outlook",
            "description": "Microsoft Outlook is a free app that helps you stay on top of messages, news, and things you need to do. It has SMS, email, alarms & calendar, news, and notes. All of this, with security you can count on.",
            "subtitle": "Personalized. Organized. Connected"
        },
        "hi-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook एक नि:शुल्क ऐप है जो आपको संदेशों, समाचारों और उन चीजों में आगे रखने में मदद करता है जिन्हें करने की आपको आवश्यकता होती है. SMS, ईमेल, कैलेंडर, वीडियो और नोट्स के लिए एक ऐप. इन सभी के साथ ऐसी सुरक्षा जिस पर आप भरोसा कर सकते हैं.",
            "subtitle": "व्यक्तिगत. व्यवस्थित. संयोजित"
        },
        "as-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook হৈছে এটা বিনামূলীয়া এপ্প্ যিয়ে আপোনাক বাৰ্তা, বাতৰি আৰু সেই বিষয়বোৰৰ শীৰ্ষত থাকিবলৈ সহায় কৰে যিবোৰ আপুনি কৰাৰ প্ৰয়োজন। SMS, ই-মেইল, কেলেণ্ডাৰ, ভিডিঅ’ আৰু টোকাসমূহৰ বাবে এটা এপ্প্। এই সকলো আৰু আপুনি নিৰ্ভৰ কৰিব পৰা সুৰক্ষা লাভ কৰক।",
            "subtitle": "ব্যক্তিগত। সংগঠিত। সংযোজিত"
        },
        "bn-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook একটি মুক্ত অ্যাপ যা আপনাকে বার্তা, সংবাদ এবং আপনার যা করা প্রয়োজন তা সম্পর্কে আপডেট থাকতে সহায়তা করে। SMS, ইমেইল, ক্যালেন্ডার, ভিডিও এবং নোটসমূহের জন্য একটি অ্যাপ। নিরাপদ এই সমস্ত কিছুর উপর আপনি ভরসা করতে পারেন।",
            "subtitle": "ব্যক্তিগতকৃত। সুসংগঠিত। সংযুক্ত"
        },
        "gu-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook એક મફત એપ્લિકેશન છે જે તમને સંદેશા, સમાચાર અને તમારી જરૂરિયાતની વસ્તુઓ અંગે તમને સૌથી આગળ રહેવામાં મદદ કરે છે. SMS, ઈમેલ, કૅલેન્ડર, વિડિયો અને નોટ્સ બધા માટે એક જ એપ્લિકેશન. આ બધું જ એક એવી સુરક્ષા સાથે જેના પર તમે ભરોસો કરી શકો છો.",
            "subtitle": "વ્યક્તિગત કરેલ. વ્યવસ્થિત. કનેક્ટ કરેલ"
        },
        "kn-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook ಒಂದು ಉಚಿತ ಅಪ್ಲಿ ಆಗಿದ್ದು, ನೀವು ಮಾಡಬೇಕಾದ ಸಂದೇಶಗಳು, ಸುದ್ದಿಗಳು ಮತ್ತು ವಿಷಯಗಳ ಮೇಲೆ ಉಳಿಯಲು ಸಹಾಯ ಮಾಡುತ್ತದೆ. SMS, ಇಮೇಲ್, ಕ್ಯಾಲೆಂಡರ್, ವೀಡಿಯೊ ಮತ್ತು ಟಿಪ್ಪಣಿಗಳಿಗಾಗಿ ಒಂದು ಅಪ್ಲಿಕೇಶನ್. ಇದೆಲ್ಲವನ್ನು ನೀವು ಭರವಸೆ ಇರಿಸಬಹುದಾದ ಭದ್ರತೆಯೊಂದಿಗೆ.",
            "subtitle": "ವೈಯಕ್ತೀಕರಣಗೊಂಡಿದೆ. ಸಂಘಟಿತವಾಗಿದೆ. ಸಂಪರ್ಕಿತವಾಗಿದೆ"
        },
        "ks-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook is a free app that helps you stay on top of messages, news, and things you need to do. It has SMS, email, alarms & calendar, news, and notes. All of this, with security you can count on.",
            "subtitle": "Personalized. Organized. Connected"
        },
        "ml-IN": {
            "name": "Outlook",
            "description": "സന്ദേശങ്ങൾ, വാർത്തകൾ, നിങ്ങൾ ചെയ്യേണ്ട കാര്യങ്ങൾ എന്നിവയിൽ തുടരാൻ സഹായിക്കുന്ന ഒരു സൗജന്യ ആപ്പാണ് Microsoft Outlook. SMS, ഇമെയിൽ, കലണ്ടർ, വീഡിയോ കൂടാതെ കുറിപ്പുകൾ എന്നിവയ്\u200Cക്കായുള്ള ഒറ്റ ആപ്പ് ആണിത്. ഇതിനൊപ്പമുള്ള സുരക്ഷ നിങ്ങൾക്ക് പ്രതീക്ഷിക്കാം.",
            "subtitle": "വ്യക്തിഗതമാക്കുക. ഓർഗനൈസ് ചെയ്യുക. ബന്ധിപ്പിക്കുക"
        },
        "mr-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook हा एक मोफत अनुप्रयोग आहे जो आपल्याला संदेश, बातम्या आणि आपल्याला करावयाच्या असलेल्या गोष्टींविषयी अद्ययावत ठेवतो. SMS, ईमेल, कॅलेंडर, व्हिडिओ आणि नोट्ससाठी एक अनुप्रयोग. हे सर्व आपण विसंबून राहू शकता अशा सुरक्षेसह एकत्रित आहे.",
            "subtitle": "वैयक्तिकृत, संघटित. कनेक्ट केलेला"
        },
        "ne-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook भनेको तपाईंलाई सन्देश, समाचार र तपाईंले गर्न आवश्यक पर्ने कुराहरू बारे जानकार राखिराख्न मद्दत गर्ने नि:शुल्क एप्लिकेसन हो। SMS, इमेल, पात्रो, भिडियो र नोटहरूका लागि एउटै एप्लिकेसन। तपाईंले यी सबै कुराहरूलाई सुरक्षाका साथमा एकसाथ प्रयोग गर्न सक्नुहुन्छ।",
            "subtitle": "व्यक्तिगिकरण गरिएको। संगठित गरिएको। जडान गरिएको"
        },
        "or-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook ହେଉଛି ଏକ ନିଃଶୁଳ୍କ ଆପ୍ଲିକେସନ୍ ଯାହା ଆପଣ କରିବାକୁଥିବା ବାର୍ତ୍ତା, ନ୍ୟୁଜ୍ ଏବଂ କାର୍ଯ୍ୟର ଶୀର୍ଷରେ ରହିବାକୁ ସାହାଯ୍ୟ କରିଥାଏ. SMS ପାଇଁ ଏକ ଆପ୍ଲିକେସନ୍, ଇମେଲ୍, କ୍ୟାଲେଣ୍ଡର୍, ଭିଡିଓ ଏବଂ ନୋଟ୍ସ. ଆପଣ ଗଣନା କରିପାରୁଥିବା ସୁରକ୍ଷା ସହ ସମସ୍ତ.",
            "subtitle": "ବ୍ୟକ୍ତିଗତକୃତ. ଆୟୋଜିତ. ସଂଯୋଜିତ"
        },
        "pa-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook ਇੱਕ ਫਰੀ ਐਪਲੀਕੇਸ਼ਨ ਹੈ ਜੋ ਤੁਹਾਨੂੰ ਸੁਨੇਹਿਆਂ, ਸਮਾਚਾਰ ਅਤੇ ਤੁਹਾਡੀ ਲੋੜੀਂਦੀ ਚੀਜ਼ਾਂ ਬਾਰੇ ਜਾਣੂ ਰਹਿਣ ਵਿੱਚ ਮਦਦ ਕਰਦੀ ਹੈ। SMS, ਈਮੇਲ, ਕੈਲੰਡਰ, ਵੀਡੀਓ ਅਤੇ ਨੋਟਸ ਲਈ ਇੱਕੋ ਐਪਲੀਕੇਸ਼ਨ। ਇਹ ਸਭ ਕੁਝ ਇਕੱਠਾ ਅਜਿਹੀ ਸੁਰੱਖਿਆ ਨਾਲ ਜਿਸ ‘ਤੇ ਤੁਸੀਂ ਭਰੋਸਾ ਕਰ ਸਕਦੇ ਹੋ।",
            "subtitle": "ਵਿਅਕਤੀਗਤ। ਵਿਵਸਥਿਤ। ਜੁੜਿਆ ਹੋਇਆ"
        },
        "sa-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook is a free app that helps you stay on top of messages, news, and things you need to do. It has SMS, email, alarms & calendar, news, and notes. All of this, with security you can count on.",
            "subtitle": "Personalized. Organized. Connected"
        },
        "sd-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook is a free app that helps you stay on top of messages, news, and things you need to do. It has SMS, email, alarms & calendar, news, and notes. All of this, with security you can count on.",
            "subtitle": "Personalized. Organized. Connected"
        },
        "ta-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook என்பது மெசேஜ்கள், செய்திகள் மற்றும் நீங்கள் செய்ய வேண்டிய விஷயங்கள் பற்றி தெரிந்துகொள்ள உதவும் ஒரு இலவச பயன்பாடாகும். எஸ்எம்எஸ், மின்னஞ்சல், நாள்காட்டி, வீடியோ மற்றும் குறிப்புகளுக்கான ஒரு பயன்பாடு. இவையனைத்துமே உங்கள் நம்பகத்தன்மைக்கேற்ப பாதுகாப்புடன் கிடைக்கும்.",
            "subtitle": "பிரத்தியேகமானது. ஒழுங்கமைக்கப்பட்டது. இணைக்கப்பட்டது"
        },
        "te-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook అనేది ఉచిత అప్లికేషన్, ఇది సందేశాలు, వార్తలు మరియు మీరు చేయవలసిన పనుల పైన ఉన్నతంగా ఉండటానికి సహాయపడుతుంది. SMS, ఇమెయిల్, క్యాలెండర్, వీడియో మరియు గమనికల కోసం ఒకే అప్లికేషన్. ఇవన్నీ కలిసి మీరు కోరుకుంటున్న భద్రతతో లభిస్తున్నాయి.",
            "subtitle": "వ్యక్తిగతీకరించబడింది. నిర్వహించబడింది. అనుసంధానించబడింది"
        },
        "und-bod": {
            "name": "Outlook",
            "description": "Microsoft Outlook is a free app that helps you stay on top of messages, news, and things you need to do. It has SMS, email, alarms & calendar, news, and notes. All of this, with security you can count on.",
            "subtitle": "Personalized. Organized. Connected"
        },
        "mai-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook is a free app that helps you stay on top of messages, news, and things you need to do. It has SMS, email, alarms & calendar, news, and notes. All of this, with security you can count on.",
            "subtitle": "Personalized. Organized. Connected"
        },
        "kok-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook हें एक फुकट ऍप्लिकेशन जे तुमकां संदेशाचें, खबरांचे आनी तुमी करूंक जाय त्या गजालींचे वयर रावूंक आदार करता. SMS, ईमेल, कॅलेंडर, व्हिडियो आनी टिपां खातीर एक ऍप्लिकेशन. सुरक्षे वांगडा हें सगळें तुमी गणटी करूंक शकतात.",
            "subtitle": "वैयक्तीक केल्ले. संघटीत केल्लें. कनॅक्ट केल्ले"
        },
        "mni-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook is a free app that helps you stay on top of messages, news, and things you need to do. It has SMS, email, alarms & calendar, news, and notes. All of this, with security you can count on.",
            "subtitle": "Personalized. Organized. Connected"
        },
        "doi-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook is a free app that helps you stay on top of messages, news, and things you need to do. It has SMS, email, alarms & calendar, news, and notes. All of this, with security you can count on.",
            "subtitle": "Personalized. Organized. Connected"
        },
        "ur-IN": {
            "name": "Outlook",
            "description": "Microsoft Outlook ایک ایسی مفت ایپ ہے جو آپ کو اپنے پیغامات، خبروں اور کرنے والے دیگر ضروری کاموں کے ساتھ قدم بہ قدم ہم آہنگ رکھتی ہے۔ SMS، ای میل، کیلنڈر، وِیڈیو اور نوٹس سب کے لئے ایک ہی ایپ۔ اور ان سب کے ساتھ ایسی سیکورٹی بھی جس پر آپ مکمل بھروسہ کر سکتے ہیں۔",
            "subtitle": "آپ کی پسند کے عین مطابق۔ منظم. باہم متصل"
        }
    },
    "default_locale": "en-US"
}

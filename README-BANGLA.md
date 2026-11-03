# Shazid Hossain — Portfolio Website

এটি একটি static portfolio website। কোনো paid website builder বা backend লাগবে না। GitHub Pages দিয়ে বিনামূল্যে public করা যাবে।

## ১) কী কী পরিবর্তন করতে পারবেন?
- নাম, পরিচিতি, About, Experience, Skills: `content.js` ফাইলে।
- নিজের ছবি: `assets/images/profile.jpg` নামে ছবি রাখুন, তারপর `content.js`-এ `profileImage: "assets/images/profile.jpg"` দিন।
- CV: নিজের updated CV `assets/Shazid-Hossain-CV.pdf` নামে রাখুন, তারপর `resumePath`-এ ওই path দিন।
- Project ছবি/ভিডিও: `assets/images/` বা `assets/videos/`-এ ফাইল রাখুন। `content.js`-এর project-এর `media`-তে path দিন।
- Project link: `link`-এ YouTube, Behance, Google Drive বা অন্য public link দিন।

## ২) আগে নিজের কম্পিউটারে দেখুন
`index.html` ফাইলটি Chrome-এ double-click করে খুলুন। বেশিরভাগ content দেখা যাবে। পরে GitHub Pages-এ publish করার আগে সব ছবি/লিংক পরীক্ষা করুন।

## ৩) GitHub-এ account খুলুন
1. https://github.com এ যান।
2. Sign up করে account তৈরি/লগইন করুন।
3. Email verify করুন।

## ৪) Website upload করুন
1. GitHub-এ উপরের `+` → `New repository` চাপুন।
2. Repository name দিন: `shazid-portfolio`
3. `Public` নির্বাচন করুন।
4. `Add a README file` চাইলে tick দিতে পারেন।
5. `Create repository` চাপুন।
6. Repository-তে `Add file` → `Upload files` চাপুন।
7. ZIP ফাইলটি আগে Extract করুন। ZIP নিজে upload করবেন না—ভেতরের `index.html`, `style.css`, `script.js`, `content.js`, `assets` folder এবং README upload করবেন।
8. Upload শেষ হলে নিচে `Commit changes` চাপুন।

## ৫) GitHub Pages চালু করুন
1. Repository-র `Settings` খুলুন।
2. বাম পাশ থেকে `Pages` নির্বাচন করুন।
3. `Build and deployment` অংশে `Deploy from a branch` নির্বাচন করুন।
4. Branch হিসেবে `main` এবং folder হিসেবে `/(root)` নির্বাচন করুন।
5. `Save` চাপুন।
6. কিছুক্ষণ পর Pages পেজে Website URL দেখাবে। সাধারণত URL হবে:
   `https://YOUR-USERNAME.github.io/shazid-portfolio/`

## ৬) পরে Website update করবেন কীভাবে?
1. Repository খুলুন।
2. `content.js` ফাইল খুলে pencil/Edit আইকনে চাপুন।
3. লেখা পরিবর্তন করুন, নিচে `Commit changes` চাপুন।
4. ছবি বা ভিডিও যোগ করতে `Add file` → `Upload files` ব্যবহার করুন।
5. Publish হতে কিছু সময় লাগতে পারে; তারপর URL refresh করুন।

## গুরুত্বপূর্ণ
- GitHub Pages public website host করে; repository ও website-এর content অন্যরা দেখতে পারবে। কোনো password, private customer data বা confidential company file upload করবেন না।
- INNI বা অন্য প্রতিষ্ঠানের কাজ দেখানোর আগে নিশ্চিত হোন যে সেগুলো portfolio-তে প্রকাশ করার অনুমতি আছে।
- বড় ভিডিও সরাসরি GitHub-এ না দিয়ে YouTube/Vimeo-তে upload করে link দিন। ছোট preview clip হলে optimize করে ব্যবহার করুন।
- CV-তে থাকা ব্যক্তিগত ফোন নম্বর public করতে চাইলে আগে ভেবে নিন। এই template-এ email contact রাখা হয়েছে।
- এখানে কোনো ভুয়া sales/reach/engagement metric যোগ করা হয়নি। বাস্তব data থাকলে পরে যুক্ত করুন।

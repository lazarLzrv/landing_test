index.html / landing page-a трябва да е пусната от сървър за да няма CORS локално и за да не отваря tree-то на реакт апп-а - толзвал съм browser-sync за теста

browser-sync start --server --files "index.html"

във build-a трябва да се променят пътищата за да зарежда файловете вместо '/' './'

или в package.json да се добави "homepage": "http://example.com/london", и ти сетва правилно пътищата




1. Dự án này được khởi tạo bằng create-react-app --template typescipt\
   This project start with create-react-app --template typescript

2. Tôi bắt đầu crawl data từ trang https://www.formula1.com/en/results.html/2023/races.html (RACE) bằng việc custom lại git repo [https://blog.logrocket.com/node-js-web-scraping-tutorial/#what-web-crawler.] (https://github.com/Jordanirabor/workers-tutorial)\
    I start to crawl data from the website https://www.formula1.com/en/results.html/2023/races.html by recustom git repo of https://github.com/Jordanirabor/workers-tutorial\
    2.1 Sau khi đọc code từ workers-tutorial, crawl thử thì tôi bị lỗi tôi đã fix nhờ cheeriojs/cheerio#613 ####After read and try coding from workers-tutorial, in the process of crawl data i fixed the error form this cheeriojs/cheerio#613\
    2.1.1 Tôi đã sử dụng chatGPT để tạo hàm format lại dữ liệu để đẩy lên firebase ####I used chatGTP to create a function to format data get form cheerio and push it to firebase\

3. Tôi đã sử dụng bản tự custome dựa trên workers-tutorial để tìm các attributes data-name,data-value trên trang RACE sau đó render các URL và đưa chúng vào https://www.octoparse.com/ để tiến hành crawl data\
    I used my own custome worker base on workers-tutorial to find all attributes of data-name,data-value on RACE then then render needed URLs và import them to https://www.octoparse.com/ for crawl data process







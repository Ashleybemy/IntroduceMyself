# IntroduceMyself
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giới thiệu bản thân</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77a6f7 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        .showcase {
            min-height: 400px;
            background: url('https://via.placeholder.com/800x400') no-repeat 0 -400px;
            text-align: center;
            color: #fff;
        }
        .showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        .showcase p {
            font-size: 20px;
        }
        #main {
            padding: 20px;
        }
        .footer {
            padding: 20px;
            margin-top: 20px;
            color: #fff;
            background-color: #333;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Giới thiệu bản thân</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">Về tôi</a></li>
                    <li><a href="#skills">Kỹ năng</a></li>
                    <li><a href="#contact">Liên hệ</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section class="showcase">
        <div class="container">
            <h1>Chào mừng đến với trang của tôi</h1>
            <p>Tôi là [Vương Minh Quân], [sinh viên trường đại học FPT ] từ [Đà Nẵng].</p>
        </div>
    </section>
    <div class="container" id="main">
        <section id="about">
            <h2>Về tôi</h2>
            <p>Tôi là một người đam mê [tạo ra những thứ mới]. Với ước muốn được làm điều đó trong [lĩnh vực công nghệ], tôi luôn cố gắng hoàn thiện bản thân và mang lại giá trị cho cộng đồng.</p>
        </section>
        <section id="skills">
            <h2>Kỹ năng</h2>
            <ul>
                <li>Có thể làm chủ mọi tình huống</li>
                <li>Có thể contact tốt với tất cả mọi người</li>
                <li>Tự tin vào khả năng của bản thân</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Liên hệ</h2>
            <p>Email: <a href="quanvuong22122005@gmail.com">youremail@example.com</a></p>
            <p>Điện thoại: [0968019297]</p>
        </section>
    </div>
    <footer class="footer">
        <p>Bản quyền &copy; 2024. Mọi quyền được bảo lưu.</p>
    </footer>
</body>
</html>

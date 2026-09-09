<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>CLASS 9A1</title>

    <link rel="stylesheet" href="style.css">

    <!-- Font -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;600;700&family=Montserrat:wght@400;500;600;700;800&display=swap" rel="stylesheet">

</head>

<body>

    <!-- LOADING -->
    <div class="loader" id="loader">
        <h1>9A1</h1>
    </div>


    <!-- NAVIGATION -->

    <nav>

        <div class="logo">
            9A1<span>.</span>
        </div>

        <div class="nav-links">

            <a href="#home">Trang chủ</a>
            <a href="#about">Giới thiệu</a>
            <a href="#members">Thành viên</a>
            <a href="#gallery">Kỷ niệm</a>

        </div>

        <button class="menu-btn" id="menuBtn">
            ☰
        </button>

    </nav>


    <!-- HERO -->

    <section class="hero" id="home">

        <div class="grid-background"></div>

        <div class="hero-content">

            <p class="small-title">
                CHÚNG TA LÀ
            </p>

            <h1 class="hero-title">
                CLASS 9A1
            </h1>

            <p class="hero-description">
                Một tập thể, một hành trình và thật nhiều kỷ niệm.
            </p>

            <a href="#about" class="hero-button">
                Khám phá ↓
            </a>

        </div>


        <!-- ẢNH LỚP -->

        <div class="hero-image-container">

            <img 
                src="assets/hero.png" 
                alt="CLASS 9A1"
                class="hero-image"
            >

        </div>


        <div class="scroll-text">
            SCROLL TO EXPLORE
        </div>

    </section>


    <!-- GIỚI THIỆU -->

    <section class="about section" id="about">

        <div class="section-number">
            01
        </div>

        <div class="about-content reveal">

            <p class="section-tag">
                GIỚI THIỆU
            </p>

            <h2>
                Chúng ta là <span>9A1</span>
            </h2>

            <p>
                Đây là nơi lưu giữ những khoảnh khắc đáng nhớ của tập thể
                CLASS 9A1. Những ngày đi học, những buổi vui chơi và cả
                những câu chuyện mà sau này chúng ta sẽ luôn nhớ.
            </p>

            <p>
                Mỗi người đều khác nhau, nhưng khi ở cùng nhau,
                chúng ta tạo nên một tập thể đặc biệt.
            </p>

        </div>

    </section>


    <!-- THỐNG KÊ -->

    <section class="stats">

        <div class="stat reveal">

            <h2>9A1</h2>

            <p>TẬP THỂ</p>

        </div>


        <div class="stat reveal">

            <h2>∞</h2>

            <p>KỶ NIỆM</p>

        </div>


        <div class="stat reveal">

            <h2>2026</h2>

            <p>HÀNH TRÌNH</p>

        </div>

    </section>


    <!-- THÀNH VIÊN -->

    <section class="members section" id="members">

        <div class="section-header reveal">

            <p class="section-tag">
                THÀNH VIÊN
            </p>

            <h2>
                Những mảnh ghép của <span>9A1</span>
            </h2>

        </div>


        <div class="member-grid">


            <div class="member-card reveal">

                <div class="member-avatar">
                    01
                </div>

                <h3>Thành viên 1</h3>

                <p>
                    Chức vụ / Mô tả
                </p>

            </div>


            <div class="member-card reveal">

                <div class="member-avatar">
                    02
                </div>

                <h3>Thành viên 2</h3>

                <p>
                    Chức vụ / Mô tả
                </p>

            </div>


            <div class="member-card reveal">

                <div class="member-avatar">
                    03
                </div>

                <h3>Thành viên 3</h3>

                <p>
                    Chức vụ / Mô tả
                </p>

            </div>


            <div class="member-card reveal">

                <div class="member-avatar">
                    04
                </div>

                <h3>Thành viên 4</h3>

                <p>
                    Chức vụ / Mô tả
                </p>

            </div>


        </div>


        <p class="custom-note">
            Bạn có thể thêm toàn bộ thành viên của lớp ở đây sau.
        </p>

    </section>


    <!-- GALLERY -->

    <section class="gallery section" id="gallery">

        <div class="section-header reveal">

            <p class="section-tag">
                KỶ NIỆM
            </p>

            <h2>
                Những khoảnh khắc <span>không thể quên</span>
            </h2>

        </div>


        <div class="gallery-grid">


            <div class="gallery-item big reveal">

                <div class="placeholder-image">
                    ẢNH KỶ NIỆM 01
                </div>

            </div>


            <div class="gallery-item reveal">

                <div class="placeholder-image">
                    ẢNH KỶ NIỆM 02
                </div>

            </div>


            <div class="gallery-item reveal">

                <div class="placeholder-image">
                    ẢNH KỶ NIỆM 03
                </div>

            </div>


        </div>

    </section>


    <!-- QUOTE -->

    <section class="quote">

        <div class="quote-content reveal">

            <p>
                "Sau này có thể chúng ta sẽ đi những con đường khác nhau..."
            </p>

            <h2>
                Nhưng 9A1 sẽ luôn là một phần thanh xuân của chúng ta.
            </h2>

        </div>

    </section>


    <!-- FOOTER -->

    <footer>

        <h2>
            CLASS <span>9A1</span>
        </h2>

        <p>
            Những năm tháng mà chúng ta sẽ không bao giờ quên.
        </p>

        <div class="footer-line"></div>

        <small>
            © 2026 CLASS 9A1
        </small>

    </footer>


    <script src="script.js"></script>

</body>
</html>

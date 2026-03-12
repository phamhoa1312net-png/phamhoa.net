index.html<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phạm Hòa - Bio Link</title>
    <style>
        /* Cài đặt cơ bản */
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: white;
            overflow: hidden; /* Ẩn thanh cuộn */
        }

        /* Vùng chứa nền 3D */
        #vanta-bg {
            width: 100%;
            height: 100vh;
            position: absolute;
            z-index: -1;
        }

        /* Vùng chứa nội dung chính */
        .container {
            position: relative;
            z-index: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100%;
            padding: 20px;
            text-align: center;
            box-sizing: border-box;
            background: rgba(0, 0, 0, 0.4); /* Lớp phủ mờ để dễ đọc chữ */
        }

        /* Tiêu đề trên cùng (Chữ đỏ phát sáng) */
        .top-logo {
            color: #ff2a2a;
            font-size: 24px;
            font-weight: 900;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 0 0 10px #ff2a2a, 0 0 20px #ff0000;
            margin-bottom: 5px;
        }

        .sub-logo {
            font-size: 10px;
            color: #888;
            letter-spacing: 3px;
            margin-bottom: 40px;
        }

        /* Tên chính (Chữ in nghiêng to) */
        .main-name {
            font-size: 40px;
            font-weight: 900;
            font-style: italic;
            margin-bottom: 15px;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.8);
        }

        /* Đoạn mô tả */
        .description {
            font-size: 15px;
            line-height: 1.6;
            max-width: 400px;
            margin-bottom: 40px;
            color: #e0e0e0;
        }

        /* Vùng chứa các nút link */
        .links-wrapper {
            width: 100%;
            max-width: 350px;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        /* Style chung cho các nút */
        .btn {
            display: block;
            width: 100%;
            padding: 16px 0;
            border-radius: 30px;
            text-decoration: none;
            color: white;
            font-size: 16px;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
            border: 1px solid rgba(255,255,255,0.1);
        }

        /* Hiệu ứng khi chạm vào nút */
        .btn:active {
            transform: scale(0.95);
        }

        /* Màu sắc từng nút */
        .btn-zalo {
            background: linear-gradient(135deg, #0088FF, #0055cc);
        }
        
        .btn-tiktok {
            background: linear-gradient(135deg, #000000, #333333);
            border: 1px solid #25F4EE;
        }

        .btn-bio {
            background: linear-gradient(135deg, #a855f7, #3b82f6);
        }
    </style>
</head>
<body>

    <div id="vanta-bg"></div>

    <div class="container">
        <div class="top-logo">PHẠM HÒA</div>
        <div class="sub-logo">DIGITAL & SOCIAL MEDIA</div>

        <div class="main-name">Phạm Hòa</div>

        <div class="description">
            Kết nối và hỗ trợ các dịch vụ mạng xã hội chuyên nghiệp. Tham gia cộng đồng của chúng tôi ngay hôm nay!
        </div>

        <div class="links-wrapper">
            <a href="https://zalo.me/g/alowvv673" target="_blank" class="btn btn-zalo">Tham gia Nhóm Zalo</a>
            
            <a href="https://www.tiktok.com/@phamhoa.net?_r=1&_t=ZS-94dIw6bspWa" target="_blank" class="btn btn-tiktok">Kênh TikTok</a>
            
            <a href="https://beacons.ai/phamhoa.net" target="_blank" class="btn btn-bio">Xem Link Bio</a>
        </div>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r134/three.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.net.min.js"></script>
    
    <script>
        VANTA.NET({
            el: "#vanta-bg",
            mouseControls: true,
            touchControls: true,
            gyroControls: true, /* Hỗ trợ xoay màn hình điện thoại */
            minHeight: 200.00,
            minWidth: 200.00,
            scale: 1.00,
            scaleMobile: 1.00,
            color: 0x3b82f6, /* Màu của các đường nối 3D (Xanh dương) */
            backgroundColor: 0x080814, /* Màu nền tối */
            points: 12.00,
            maxDistance: 22.00,
            spacing: 18.00
        })
    </script>
</body>
</html>

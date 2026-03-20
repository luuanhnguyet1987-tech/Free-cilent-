<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FREE CILENT FILE</title>

<style>
body {
    margin: 0;
    background: radial-gradient(circle at top, #1a0026, #000);
    font-family: monospace;
    color: #c77dff;
    text-align: center;
}

/* Tiêu đề */
h1 {
    margin-top: 40px;
    font-size: 42px;
    letter-spacing: 2px;
    text-shadow: 
        0 0 5px #c77dff,
        0 0 15px #9d4edd,
        0 0 30px #7b2cbf;
}

/* Button */
.btn {
    display: block;
    margin: 15px auto;
    padding: 15px;
    width: 320px;
    border: 2px solid #c77dff;
    color: #c77dff;
    background: rgba(199,125,255,0.05);
    cursor: pointer;
    font-size: 16px;
    border-radius: 12px;
    transition: 0.3s;
}

.btn:hover {
    background: #c77dff;
    color: black;
    box-shadow: 0 0 20px #c77dff;
}

/* Ghi chú nhỏ */
.note {
    font-size: 12px;
    opacity: 0.7;
    margin-top: -10px;
    margin-bottom: 10px;
}

/* Box script */
.script-box {
    width: 90%;
    max-width: 850px;
    margin: 30px auto;
    padding: 15px;
    border: 1px solid #c77dff;
    border-radius: 12px;
    text-align: left;
    white-space: pre-wrap;
    background: rgba(199,125,255,0.05);
    box-shadow: 0 0 15px rgba(199,125,255,0.2);
}

/* Code */
.code {
    cursor: pointer;
    color: #e0aaff;
}

.code:hover {
    text-decoration: underline;
}

/* Footer */
.footer {
    margin-top: 20px;
    opacity: 0.6;
}
</style>
</head>

<body>

<h1>⚡ FREE CILENT FILE ⚡</h1>

<!-- Buttons -->
<button class="btn" onclick="openLink('https://play.google.com/store/apps/details?id=com.geniuscloud.overseasplatform')">
VMOS
</button>

<div class="note">
tạo tài khoản bằng email 10 phút rồi đăng nhập Vmos sẽ được free 6 tiếng, hết thời gian thì vô phần cài đặt, đăng xuất rồi làm lại từ đầu để được vô hạn
</div>

<button class="btn" onclick="openLink('https://www.mediafire.com/file/sx89dhptqd6ym9y/Delta_X_VNG_2.711_BANDISHARE.apk/file')">
Cilent Delta X VNG
</button>

<button class="btn" onclick="openLink('https://www.mediafire.com/file/nt8w10zmytnpu9y/ru.zdevs.zarchiver_1.0.10.apk/file')">
ZAchiVer APK (Auto Script)
</button>

<button class="btn" onclick="openLink('https://smailpro.com/vi')">
Tạo Gmail 10 phút
</button>

<!-- Script -->
<h2>📜 Script Kaitun Here</h2>

<div class="script-box">
<div class="code" onclick="copyCode()">
Config = {
    Team = "Pirates",
    Configuration = {
        HopWhenIdle = true,
        AutoHop = true,
        AutoHopDelay = 60 * 60,
        FpsBoost = false,
        blackscreen = true
    },
    Items = {

        -- Melees 
        AutoFullyMelees = true,

        -- Swords 
        Saber = true,
        CursedDualKatana = false,

        -- Guns 
        SoulGuitar = false,

        -- Upgrades 

        RaceV2 = false

    },
    Settings = {
        StayInSea2UntilHaveDarkFragments = false
    }
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/hhl29042008-ops/script/refs/heads/main/cac"))()
</div>
</div>

<div class="footer">Click vào code để copy</div>

<script>
function openLink(url) {
    window.open(url, "_blank");
}

function copyCode() {
    const text = document.querySelector(".code").innerText;
    navigator.clipboard.writeText(text);
    alert("Đã copy script!");
}
</script>

</body>
</html>

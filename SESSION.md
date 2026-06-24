# Session - Ngangooancuc 3D Game
- Task: Khắc phục lỗi lắc đầu và tối ưu hiển thị ảnh Boss.
- State: Đã xóa logic `lookAt` gây lắc và chuyển phần đầu của quái vật thành `Sprite` (2D plane luôn hướng về camera). Đảm bảo luôn nhìn rõ ảnh Boss và không bị rung lắc. Sẵn sàng chơi thử.

- Task: Tao game Line 98 classic trong FORFUN de giai tri.
- State: Da them file Line98Classic.html voi ban co ban choi duoc: 9x9 board, chon/di chuyen bi, sinh 3 bi moi sau moi luot, xoa line tu 5 tro len, tinh diem va man hinh game over.

- Task: Chinh giao dien Line 98 sang phong cach co dien theo anh mau.
- State: Da thay UI bang top bar den, board xam bevel, bi 3D va bo sidebar; dang giu gameplay cu va chinh rule spawn 3 bi cho gan ban goc hon.

- Task: Lam hieu ung no khi an diem va tang toc do di chuyen cho Line 98.
- State: Da them particle explosion khi xoa line, rut ngan flash, tang toc animation di chuyen va don lai code thua.

- Task: Them menu Start, Save, Highscore cho Line 98.
- State: Da them menu row tren top bar, Save luu tien trinh vao localStorage, Highscore mo hop thong tin, Start reset va bat dau van moi.

- Task: Di chuyen nut sang le trai, them Pause va preview 3 bong truoc luot moi cho Line 98.
- State: Da tach menu sang dock ben trai, them nut Pause/Resume, doi preview thanh 3 bong mau nam tren dong ho, va dong bang timer/animation khi tam dung.

- Task: Tang do lon va do ro cho game Line 98 de phu hop nguoi gia.
- State: Da tang kich thuoc so, timer, preview bong va bo sung thong so bi/board lon hon; giam hieu ung bong bong va gloss de giao dien ro va de nhin hon.

- Task: Lam giao dien Line 98 dep hon nhung van don gian.
- State: Da lam lai tong mau sang va deu hon, giam neon/thieu thua, bo chi tiet rối, giu top bar va board ro rang hon voi left dock gon va preview/dong ho dong bo.

- Task: Lam lai hinh vien bi Line 98 de dep va de nhin hon.
- State: Da doi palette sang mau mem hon, giam bong va gloss cua bi, lam preview va bi tren board thanh net sach va it loe loet hon.

- Task: Lam mau vien bi Line 98 nhan hon va nhan nhan hon.
- State: Da doi palette sang cac gam mau trung tinh hon, giam saturation va highlight, lam bi va preview mem mat va de nhin hon.

- Task: Phan mau vien bi ro hon de tranh bi nham mau.
- State: Da doi palette sang cac hue tach biet ro rang hon va giam highlight/outline de cac vien bi de nhan dien hon trong luc van giu tong mau mem.

- Task: Moi lan khoi dong game phai ra map moi ngau nhien thay vi map cu co dinh.
- State: Da bo auto-load save luc startup, va resetGame nay sinh opening board moi voi so bi dau vao ngau nhien hon mot chut de moi lan mo game co map rieng.

- Task: Lam vien bi phan mau ro hon de de phan biet giua cac mau gan nhau.
- State: Da doi palette sang bo hue tach biet manh hon (xanh, xanh la, cam, tim, do, vang) va tang do noi cua vien bien/outline de cac mau khong bi dính nhau khi nhin nhanh.

- Task: Lam highlight cua vien bi mem va mo hon.
- State: Da giam do sang cua highlight tren bi va preview, thu gon vung sang va lam vien soi goc mem hon de bi tru mat hon.

- Task: Chuyen highlight vien bi thanh 1 vet trang mo nho.
- State: Da bo diem sang tron, thay bang mot vet highlight mo ngan tren mat bi va giu vien ngoai cua qua bi rieng de mat bi sach hon.

- Task: Khi chon 1 vien bi thi no nhun len xuong nhe nhu qua bong.
- State: Da them nhip bob theo sin cho vien bi duoc chon va cho vong chon bam theo dao dong do, tao cam giac bong nay nhe.

- Task: Vien bi duoc chon can nhun va dẹt nhe nhu bong that.
- State: Da doi drawBall sang scale ngang/doc rieng, tao squash & stretch nhe cho vien bi dang chon trong luc van giu nhip bob.
- Task: Luu Line 98 hien tai thanh ban Classic va them mot mode Arcade trong cung file.
- State: Da giu Classic lam gameplay goc, them nut chuyen Classic/Arcade, Arcade co timer dem nguoc, toc do di chuyen nhanh hon, nhieu bi hon moi luot, co bonus thoi gian khi an diem, va da sua finishMove de chay on dinh.

- Task: Nang cap Arcade mode voi nhiem vu ngan, bi dac biet, ap luc theo nhip, chuong ngai va do kho tang theo diem.
- State: Da them quest ngau nhien theo luot, bi dac biet gold/bomb, block chuyen dong theo wave, toc do Arcade tang theo diem va so luot, preview hien thi bi dac biet, va bomb co the pha khu vuc xung quanh.

- Task: Khong khởi động duoc Arcade mode.
- State: Da tim ra nguyen nhan la thieu event listener cho nut Classic/Arcade, va da gan click handler goi `setMode("classic")` / `setMode("arcade")` de chuyen mode dung.

- Task: Them huong dan cho 2 mode va menu Tutorials.
- State: Da them nut Tutorials trong left dock va overlay huong dan rieng cho Classic/Arcade, co the mo/dong bang nut va phim Esc, va tu dong dong khi bat dau van moi.

- Task: Arcade mode bi no can co hinh dang 1 qua bom.
- State: Da doi render cua bomb sang hinh bom ro hon tren board va preview, voi than toi mau, day noi va ngoi no nho de phan biet voi bi thuong.

- Task: Toi uu lai giao dien cho mobile.
- State: Da dua left dock xuong thanh thanh cong cu ben duoi, tang size nut va giam top bar tren man hinh nho, lam tutorial/info overlay co the cuon va de doc hon tren dien thoai.

- Task: Chinh lai giao dien mobile theo anh man hinh.
- State: Da rut gon topbar, day board len cao hon tren mobile, thu nho dock ben duoi va nut de khong bi cut, giu menu/dock nam gon trong man hinh dien thoai.

- Task: Menu mobile van bi cat va so/bi can ro hon.
- State: Da doi mobile sang layout doc that su, cho dock nam duoi canvas va hien tron ven, dong thoi tang size so, timer, preview va bi tren board de de nhin hon.

- Task: Bố cục lại bảng menu mobile cho đẹp.
- State: Da doi mobile menu sang luoi 2 cot, cho nut Pause chay full width de khong con khoang trong xau, va giu status dong bo ben duoi menu.

- Task: Co dinh chieu ngang giao dien mobile theo kich co man hinh dien thoai.
- State: Da cho app dung `100dvw/100dvh` tren mobile va cho board lay chieu ngang lam chuan chinh, de giao dien khop be ngang man hinh va menu van nam ben duoi.

- Task: Chuan bi GitHub Pages cho Line 98.
- State: Da them `index.html` chuyen huong sang `Line98Classic.html` de Pages mo game dung ngay tu root repo.
- Task: Tang toc do di chuyen cua bi len mot chut.
- State: Da giam nhe `moveMs` cua Classic va Arcade de animation di chuyen nhanh hon, giu cam giac nhanh tay nhung khong doi luat choi.

- Task: Deploy Line 98 len GitHub voi repo moi.
- State: Da khoi tao git repo local trong FORFUN, tao commit dau tien va gan remote `origin` toi `https://github.com/ducphan2201-dev/line98-classic.git`, nhung chua the push vi may chua co thong tin xac thuc GitHub de tao repo moi.

- Task: Da co repo GitHub dich `ducphan2201-dev/Line98Clasixx`.
- State: Da doi `origin` sang `https://github.com/ducphan2201-dev/Line98Clasixx.git` va push thanh cong nhánh `main` len GitHub.

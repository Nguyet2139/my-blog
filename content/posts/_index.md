---
title: "Bài Viết"
date: 2024-01-01T00:00:00+07:00
draft: false
ShowReadingTime: false
ShowBreadCrumbs: false
ShowPostNavLinks: false
ShowWordCount: false
ShowToc: false
ShowDate: false
---

<div style="position: relative; left: 50%; right: 50%; margin-left: -50vw; margin-right: -50vw; width: 100vw; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 3rem 1rem; color: #fff;">
  <div style="max-width: 1100px; margin: 0 auto; text-align: center;">
    <h1 style="font-size: clamp(1.9rem, 3.4vw, 3rem); font-weight: 800; margin: 0;">📝 Bài Viết Lập Trình</h1>
  </div>
</div>

<!-- Hide videos, courses, and certificates on paginated pages (page/2, page/3, ...) -->
<script>
  (function(){
    function hideOnPaginated(){
      try {
        if (/\/page\//.test(location.pathname)) {
          ['featured-videos','courses','certificates'].forEach(function(id){
            var el = document.getElementById(id);
            if (el) el.style.display = 'none';
          });
        }
      } catch(e) {}
    }
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', hideOnPaginated);
    } else {
      hideOnPaginated();
    }
    window.addEventListener('pageshow', hideOnPaginated);
  })();
</script>

<!-- Custom posts grid removed to show default PaperMod list below -->

<!-- Featured Videos - Responsive row -->
<div id="featured-videos" style="position: relative; left: 50%; right: 50%; margin-left: -50vw; margin-right: -50vw; width: 100vw; background: #ffffff; padding: 2.5rem 1rem 0 1rem;">
  <div style="max-width: 1100px; margin: 0 auto;">
    <h2 style="margin: 0 0 1rem 0; font-size: 1.8rem; color: #2c3e50;">🎥 Video Nổi Bật</h2>
    <p style="margin: 0 0 1.2rem 0; color: #6b7280;">Hai video Java hay để bạn bắt đầu ngay:</p>
    <style>
      .videos-row { display: flex; gap: 1rem; justify-content: center; align-items: flex-start; flex-wrap: nowrap; overflow-x: auto; padding-bottom: 0.5rem; }
      .video-box { position: relative; width: 420px; min-width: 420px; border-radius: 14px; overflow: hidden; box-shadow: 0 8px 25px rgba(0,0,0,0.08); background:#000; }
      .video-box::before { content: ""; display: block; padding-top: 56.25%; }
      .video-box iframe { position: absolute; inset: 0; width: 100%; height: 100%; }
    </style>
    <div class="videos-row">
      <div class="video-box">
        <iframe src="https://www.youtube.com/embed/KeiFxYXRTh0" title="Java Video 1" frameborder="0" allowfullscreen style="position: absolute; inset: 0; width: 100%; height: 100%;"></iframe>
      </div>
      <div class="video-box">
        <iframe src="https://www.youtube.com/embed/ey-bPdDmYlc" title="Java Video 2" frameborder="0" allowfullscreen style="position: absolute; inset: 0; width: 100%; height: 100%;"></iframe>
      </div>
    </div>
  </div>
</div>

<!-- Courses: JavaScript Essentials 1 & 2 (detailed inline) -->
<div id="courses" style="position: relative; left: 50%; right: 50%; margin-left: -50vw; margin-right: -50vw; width: 100vw; background: #ffffff; padding: 1.5rem 1rem 0 1rem;">
  <div style="max-width: 1100px; margin: 0 auto;">
    <h2 style="margin: 0 0 1rem 0; font-size: 1.8rem; color: #2c3e50;">📚 Khóa học JavaScript Essentials 1 & 2</h2>
    <style>
      @media (min-width: 900px) { .course-grid { display:grid; grid-template-columns: 1fr 1fr; gap: 1rem; } }
      @media (max-width: 899px) { .course-grid { display:grid; grid-template-columns: 1fr; gap: 1rem; } }
    </style>
    <div class="course-grid" style="display:grid; grid-template-columns: 1fr; gap: 1rem;">
      <div style="background:#f8fafc; border-radius:16px; padding: 1.2rem 1.2rem; box-shadow: 0 10px 30px rgba(0,0,0,0.08);">
        <h3 style="margin:0 0 0.4rem 0; font-size:1.2rem; color:#1f2937;">Essentials 1 – Nền tảng JavaScript</h3>
        <p style="margin:0 0 0.6rem 0; color:#4b5563;">Phần 1 giúp bạn nắm chắc nền tảng JS hiện đại: biến, phạm vi, kiểu dữ liệu, hàm và cú pháp ES6+ để tự tin đọc/viết mã.</p>
        <ul style="margin: 0; color:#374151; line-height:1.7;">
          <li>Cơ bản ngôn ngữ: môi trường trình duyệt/Node.js; var/let/const; kiểu dữ liệu.</li>
          <li>Hàm: declaration, expression, arrow; tham số mặc định; ngữ cảnh this cơ bản.</li>
          <li>ES6+: destructuring, spread/rest, template literals.</li>
          <li>Mảng & chuỗi: map, filter, reduce, some/every, find; thao tác ngày giờ.</li>
          <li>Vòng lặp: for, for...of (so sánh với for...in).</li>
          <li>Mini‑project: todo list, bộ đếm, chuyển dark/light.</li>
        </ul>
        <p style="margin:0.6rem 0 0 0; color:#4b5563;">Kết thúc phần 1, bạn có nền tảng vững chắc để bước sang DOM, sự kiện và bất đồng bộ.</p>
      </div>
      <div style="background:#f8fafc; border-radius:16px; padding: 1.2rem 1.2rem; box-shadow: 0 10px 30px rgba(0,0,0,0.08);">
        <h3 style="margin:0 0 0.4rem 0; font-size:1.2rem; color:#1f2937;">Essentials 2 – DOM & Bất đồng bộ</h3>
        <p style="margin:0 0 0.6rem 0; color:#4b5563;">Phần 2 tập trung thao tác giao diện, xử lý sự kiện và gọi API để xây dựng ứng dụng tương tác mượt mà.</p>
        <ul style="margin: 0; color:#374151; line-height:1.7;">
          <li>Chuyển hàm đồng bộ sang bất đồng bộ: viết hàm trả về <em>Promise</em> thay cho tác vụ chặn (blocking).</li>
          <li>Tạo <em>delay(x)</em> dạng Promise bằng <em>setTimeout</em> để mô phỏng thời gian thực thi.</li>
          <li><strong>Promise.all</strong>: chạy song song các tác vụ độc lập (ví dụ: chuẩn bị A và B cùng lúc), sau đó mới chạy bước kế tiếp.</li>
          <li>Phân biệt tuần tự vs song song: khi nào nên ghép nhiều bước bằng <em>then</em>/<em>await</em>, khi nào nên gom nhóm để rút ngắn tổng thời gian.</li>
          <li><strong>async/await</strong> với <strong>try/catch</strong>: bắt lỗi, <em>return sớm</em> để dừng luồng và hiển thị thông báo phù hợp.</li>
          <li>Xử lý lỗi trong chuỗi Promise (<em>then</em>/<em>catch</em>), lan truyền lỗi (propagate) và chiến lược hiển thị lỗi thân thiện.</li>
          <li>Nâng cao: <strong>Promise.allSettled</strong> (không fail‑fast), <strong>Promise.race</strong>; hủy request với <strong>AbortController</strong>.</li>
        </ul>
        <p style="margin:0.6rem 0 0 0; color:#4b5563;">Hoàn tất phần 2, bạn có thể thao tác UI, đồng bộ dữ liệu với server và quản lý trạng thái trình duyệt.</p>
      </div>
    </div>
  </div>
</div>

 

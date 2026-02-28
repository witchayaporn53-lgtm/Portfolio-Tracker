<section id="cover" class="page-section cover-page" style="background: linear-gradient(135deg, #8B4513 0%, #D4AF37 50%, #8B4513 100%); min-height: 100vh; display: flex; align-items: center; justify-content: center; color: white;">
    <div class="container text-center">
        <div class="cover-content">
            <div class="profile-image-container mb-4">
                <img id="coverPhoto" src="https://via.placeholder.com/200" alt="Profile" class="profile-image">
            </div>
            <h1 class="display-3 fw-bold mb-3">วิชญาพร บุญเจริญ</h1>
            <h3 class="lead mb-2">Witchayaporn Yuvruang</h3>
            <p class="h5 mb-4">Mobile Student to Bright Future</p>
            <div class="divider mb-4"></div>
            <p class="mb-3"><i class="fas fa-school"></i> โรงเรียนนารีนุกูล อุบลราชธานี</p>
            <p class="mb-3"><i class="fas fa-graduation-cap"></i> ชั้นมัธยมศึกษาปีที่ 4</p>
            <p class="mb-3"><i class="fas fa-quote-left"></i> "ความเป็นไปได้นั้นไม่มีขีดจำกัด"</p>
            <div class="divider mt-4"></div>
        </div>
    </div>
</section>

<!-- PAGE 2: INTRODUCTION -->
<section id="introduction" class="page-section">
    <div class="container py-5">
        <h2 class="section-title mb-5">
            <span class="title-number">01</span> แนะนำตัว
        </h2>
        <div class="row">
            <div class="col-lg-4 mb-4">
                <div class="intro-card">
                    <img id="introPhoto" src="https://via.placeholder.com/300" alt="Profile" class="intro-image">
                    <h4 class="mt-4 mb-3">ข้อมูลส่วนตัว</h4>
                    <ul class="list-unstyled">
                        <li><strong>ชื่อ:</strong> <span id="intro_fullname">วิชญาพร บุญเจริญ</span></li>
                        <li><strong>ชื่อเล่น:</strong> <span id="intro_nickname">วิช</span></li>
                        <li><strong>วันเกิด:</strong> <span id="intro_birthday">-</span></li>
                        <li><strong>ที่อยู่:</strong> <span id="intro_address">อุบลราชธานี</span></li>
                        <li><strong>Email:</strong> <span id="intro_email">-</span></li>
                        <li><strong>Tel:</strong> <span id="intro_tel">-</span></li>
                    </ul>
                </div>
            </div>
            <div class="col-lg-8">
                <div class="intro-card">
                    <h4 class="mb-4">บุคลิกและจุดแข็ง</h4>
                    <div class="mb-4">
                        <h5>เกี่ยวกับตัวเอง</h5>
                        <p id="intro_about">ยังไม่มีข้อมูล กรุณากรอกข้อมูล</p>
                    </div>
                    <div class="mb-4">
                        <h5>ลักษณะนิสัย</h5>
                        <div id="intro_personality" class="personality-tags">
                            <span class="badge bg-primary">รอข้อมูล</span>
                        </div>
                    </div>
                    <div class="mb-4">
                        <h5>จุดแข็ง</h5>
                        <div id="intro_strengths" class="strengths-list">
                            <div class="strength-item">
                                <span class="strength-num">1.</span>
                                <span class="strength-text">รอข้อมูล</span>
                            </div>
                        </div>
                    </div>
                    <div>
                        <h5>Life Motto</h5>
                        <blockquote class="blockquote border-start ps-3">
                            <p id="intro_motto" class="mb-0">"ความเป็นไปได้นั้นไม่มีขีดจำกัด"</p>
                        </blockquote>
                    </div>
                </div>
            </div>
        </div>
        <div class="row mt-5">
            <div class="col-12">
                <button class="btn btn-primary" onclick="editSection('introduction')">
                    <i class="fas fa-edit"></i> แก้ไข
                </button>
            </div>
        </div>
    </div>
</section>

<!-- PAGE 3: ACADEMIC ACHIEVEMENT -->
<section id="academic" class="page-section bg-light">
    <div class="container py-5">
        <h2 class="section-title mb-5">
            <span class="title-number">02</span> ผลการเรียน
        </h2>
        <div class="row mb-5">
            <div class="col-lg-6">
                <div class="card h-100">
                    <div class="card-body">
                        <h5 class="card-title">GPA เฉลี่ย</h5>
                        <div class="gpa-display">
                            <div class="gpa-circle">
                                <span id="academic_gpa" class="gpa-value">3.50</span>
                            </div>
                        </div>
                        <p class="text-center text-muted">ม.4 เทอม 1-2</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-6">
                <div class="card h-100">
                    <div class="card-body">
                        <h5 class="card-title">วิชาที่เก่า (Top 3)</h5>
                        <div id="academic_top_subjects" class="subjects-list">
                            <div class="subject-item">
                                <span class="subject-name">คณิตศาสตร์</span>
                                <span class="subject-grade">A</span>
                            </div>
                            <div class="subject-item">
                                <span class="subject-name">วิทยาศาสตร์</span>
                                <span class="subject-grade">A</span>
                            </div>
                            <div class="subject-item">
                                <span class="subject-name">ภาษาอังกฤษ</span>
                                <span class="subject-grade">B+</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <button class="btn btn-primary" onclick="editSection('academic')">
                    <i class="fas fa-edit"></i> แก้ไข
                </button>
            </div>
        </div>
    </div>
</section>

<!-- PAGE 4: SKILLS & COMPETENCY -->
<section id="skills" class="page-section">
    <div class="container py-5">
        <h2 class="section-title mb-5">
            <span class="title-number">03</span> ทักษะและสมรรถนะ
        </h2>
        <div class="row">
            <div class="col-lg-6 mb-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">ทักษะวิชาการ</h5>
                        <div id="skills_academic" class="skills-grid">
                            <div class="skill-card">
                                <div class="skill-name">Problem Solving</div>
                                <div class="skill-rating">
                                    <span class="stars">★★★★☆</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-6 mb-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">ทักษะเทคนิค</h5>
                        <div id="skills_technical" class="skills-grid">
                            <div class="skill-card">
                                <div class="skill-name">MS Office</div>
                                <div class="skill-rating">
                                    <span class="stars">★★★★☆</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-6 mb-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">ทักษะอาชีพ (Soft Skills)</h5>
                        <div id="skills_professional" class="skills-grid">
                            <div class="skill-card">
                                <div class="skill-name">Communication</div>
                                <div class="skill-rating">
                                    <span class="stars">★★★☆☆</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-6 mb-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">ทักษะภาษา</h5>
                        <div id="skills_language" class="skills-grid">
                            <div class="skill-card">
                                <div class="skill-name">ไทย</div>
                                <div class="skill-rating">
                                    <span class="stars">★★★★★</span>
                                </div>
                            </div>
                            <div class="skill-card">
                                <div class="skill-name">English</div>
                                <div class="skill-rating">
                                    <span class="stars">★★★☆☆</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row mt-4">
            <div class="col-12">
                <button class="btn btn-primary" onclick="editSection('skills')">
                    <i class="fas fa-edit"></i> แก้ไข
                </button>
            </div>
        </div>
    </div>
</section>

<!-- PAGE 5: ACTIVITIES & AWARDS -->
<section id="activities" class="page-section bg-light">
    <div class="container py-5">
        <h2 class="section-title mb-5">
            <span class="title-number">04</span> กิจกรรมและรางวัล
        </h2>
        <div class="row">
            <div class="col-lg-6 mb-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">กิจกรรมในห้องเรียน</h5>
                        <div id="activities_classroom" class="activities-list">
                            <div class="activity-item">
                                <h6>หัวหน้าชั้น</h6>
                                <p class="text-muted small">ปีการศึกษา 2568</p>
                                <p>บริหารจัดการชั้นเรียน ประสานงานกับครูอาจารย์</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-6 mb-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">กิจกรรมนอกห้องเรียน</h5>
                        <div id="activities_outside" class="activities-list">
                            <div class="activity-item">
                                <h6>ชมรม</h6>
                                <p class="text-muted small">รอข้อมูล</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">รางวัลและเกียรติยศ</h5>
                        <div id="activities_awards" class="awards-list">
                            <div class="award-item">
                                <span class="award-badge"><i class="fas fa-trophy"></i></span>
                                <div class="award-content">
                                    <h6>นักเรียนดีเด่น</h6>
                                    <p class="text-muted small">โรงเรียน | 2568</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row mt-4">
            <div class="col-12">
                <button class="btn btn-primary" onclick="editSection('activities')">
                    <i class="fas fa-edit"></i> แก้ไข
                </button>
            </div>
        </div>
    </div>
</section>

<!-- PAGE 6: PROJECT PORTFOLIO -->
<section id="projects" class="page-section">
    <div class="container py-5">
        <h2 class="section-title mb-5">
            <span class="title-number">05</span> โปรเจคพอร์ตโฟลิโอ
        </h2>
        <div id="projects_list" class="row">
            <div class="col-lg-4 mb-4">
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://via.placeholder.com/300x200" alt="Project">
                    </div>
                    <div class="project-body">
                        <h5 class="project-title">Smart Home LED System</h5>
                        <p class="project-category"><span class="badge bg-success">Arduino</span></p>
                        <p class="project-description">ระบบควบคุมไฟ LED ด้วย Arduino และ App</p>
                        <div class="project-rating">
                            <span class="stars">★★★★★</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row mt-4">
            <div class="col-12">
                <button class="btn btn-primary" onclick="editSection('projects')">
                    <i class="fas fa-edit"></i> แก้ไข
                </button>
            </div>
        </div>
    </div>
</section>

<!-- PAGE 7: PERSONAL GROWTH -->
<section id="growth" class="page-section bg-light">
    <div class="container py-5">
        <h2 class="section-title mb-5">
            <span class="title-number">06</span> พัฒนาตัวเอง
        </h2>
        <div class="row">
            <div class="col-lg-6 mb-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">การพัฒนาจุดอ่อน</h5>
                        <div id="growth_weakness" class="growth-list">
                            <div class="growth-item">
                                <div class="growth-header">
                                    <h6>ไม่กล้าพูดต่อหน้าชั้น</h6>
                                    <span class="progress-badge">60%</span>
                                </div>
                                <div class="progress mb-2">
                                    <div class="progress-bar bg-warning" style="width: 60%"></div>
                                </div>
                                <p class="small text-muted">เข้าร่วมชมรมพูดในที่ชุมชน</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-6 mb-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">บทเรียนที่ได้เรียนรู้</h5>
                        <div id="growth_lessons" class="lessons-list">
                            <div class="lesson-item">
                                <h6>ความพยายามมีค่า</h6>
                                <p class="small">จากการศึกษาวิชาที่ยาก พยายามเรียนจนเข้าใจ</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row mt-4">
            <div class="col-12">
                <button class="btn btn-primary" onclick="editSection('growth')">
                    <i class="fas fa-edit"></i> แก้ไข
                </button>
            </div>
        </div>
    </div>
</section>

<!-- PAGE 8: CAREER PATH & ASPIRATION -->
<section id="career" class="page-section">
    <div class="container py-5">
        <h2 class="section-title mb-5">
            <span class="title-number">07</span> เป้าหมายอนาคต
        </h2>
        <div class="row mb-5">
            <div class="col-12">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">เป้าหมายการศึกษาต่อ (TCAS)</h5>
                        <div id="career_universities" class="universities-list">
                            <div class="university-item">
                                <div class="rank">1</div>
                                <div class="uni-content">
                                    <h6>มหาวิทยาลัยอุบลราชธานี</h6>
                                    <p>สาขา: นิติศาสตร์</p>
                                    <p class="small text-muted">เหตุผล: ใกล้บ้าน สาขาที่สนใจ</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row mb-5">
            <div class="col-lg-6 mb-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">เส้นทางอาชีพระยะยาว</h5>
                        <div id="career_path" class="career-path">
                            <div class="career-step">
                                <div class="step-number">1</div>
                                <div class="step-content">
                                    <h6>วิศวกร Software</h6>
                                    <p class="small">5 ปี</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-6 mb-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">ทำไมต้องเป็นนิติศาสตร์?</h5>
                        <p id="career_motivation">รอข้อมูล</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="row mt-4">
            <div class="col-12">
                <button class="btn btn-primary" onclick="editSection('career')">
                    <i class="fas fa-edit"></i> แก้ไข
                </button>
            </div>
        </div>
    </div>
</section>

<!-- FOOTER -->
<footer class="bg-dark text-white py-4 mt-5">
    <div class="container text-center">
        <p class="mb-2">📱 Mobile to Engineer @ Ubon University</p>
        <p class="text-muted small">Portfolio เพื่อการสมัครศึกษาต่อ TCAS 2570</p>
        <p class="text-muted small">โรงเรียนนารีนุกูล อำเภอเมือง จังหวัดอุบลราชธานี</p>
    </div>
</footer>

<!-- Modal for Editing -->
<div class="modal fade" id="editModal" tabindex="-1">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title">แก้ไขข้อมูล</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
            </div>
            <div class="modal-body" id="editFormContent">
                <!-- Form will be loaded here -->
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">ยกเลิก</button>
                <button type="button" class="btn btn-primary" onclick="saveData()">บันทึก</button>
            </div>
        </div>
    </div>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>
<script src="script.js"></script>

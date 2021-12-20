<template>
    <nav id="navbarExample" class="navbar navbar-expand-lg fixed-top navbar-light" aria-label="Main navigation">
        <div class="container">
            <a class="navbar-brand logo-text" href="/">Chemistry</a> 
        
        <button class="navbar-toggler p-0 border-0" type="button" id="navbarSideCollapse" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="navbar-collapse offcanvas-collapse" id="navbarsExampleDefault">
                <ul class="navbar-nav ms-auto navbar-nav-scroll">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#header">หน้าหลัก</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#services">ทำอะไรได้บ้าง</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#details">รายละเอียด</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#features">ฟีเจอร์</a>
                    </li>
                </ul>
                <span class="nav-item">
                    <a class="btn-solid-sm" href="https://www.facebook.com/watchara.santawee" target="_blank">ติดต่อผู้ดูแล</a>
                </span>
            </div> 
        </div> 
    </nav>

    <header id="header" class="header">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-xl-5">
                    <div class="text-container">
                        <h1 class="h1-large">ค้นหาคำตอบของคุณได้เพียงไม่กี่วินาที</h1>
                        <p class="p-large">เว็บไซต์นี้จัดทำขึ้นเพื่อศึกษาการทำโครงงาน ในวิชา เคมี ของ นายวัชระ สันทวี</p>
                        <a class="btn-solid-lg" href="#features">ไปคำนวณกันเลย!</a>
                    </div>
                </div> 
                <div class="col-lg-6 col-xl-7">
                    <div class="image-container">
                        <img class="img-fluid" src="assets/images/header-image.svg" alt="alternative" />
                    </div> 
                </div> 
            </div> 
        </div> 
    </header> 

    <div id="services" class="cards-1 bg-gray">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <h2>เว็บไซต์นี้สามารถทำอะไรได้บ้างหรอ?</h2>
                </div> 
            </div>
            <div class="row">
                <div class="col-lg-12">
                    <h5 class="card-title">สามารถคำนวณสูตรต่างๆที่เกี่ยวกับแก๊สได้!</h5>
                    <p>กฎของบอยล์ | กฎของชาร์ล | กฎของเกย์ลุสแซก | กฎรวมแก๊ส</p>
                </div>
            </div>
        </div>
    </div>

    <div id="details" class="basic-1">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-xl-7">
                    <div class="image-container">
                        <img class="img-fluid" src="assets/images/details-1.png" alt="alternative" />
                    </div> 
                </div> 
                <div class="col-lg-6 col-xl-5">
                    <div class="text-container">
                        <div class="section-title">วัชระ มีคำถามมาถามเพื่อนๆ</div>
                        <h2>ผมทำเว็บไซต์นี้ขึ้นมาเพราะอะไร?</h2>
                        <p>ไหนๆก็มาขนาดนี้แล้ว ถามเองตอบเองเลยก็แล้วกัน ผมจัดทำเว็บไซต์นี้ขึ้นเพื่อเป็นโครงงานการศึกษาในวิชาเคมี (ว30226)</p>
                        <a class="btn-solid-reg"  href="https://www.facebook.com/watchara.santawee" target="_blank">ติดต่อเลย</a>
                    </div> 
                </div> 
            </div>
        </div> 
    </div>

    <div class="basic-2">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-xl-5">
                    <div class="text-container">
                        <div class="section-title">วัชระ มีอะไรจะบอก &#62; &#60;</div>
                        <h2>โปรเจคนี้โอเพนซอร์ส</h2>
                        <p>สามารถโหลดไปใช้งานกันได้ฟรีๆเลย ที่ Github: <a href="ddd" target="_blank">https://github.com/iambestzige/gas-chemistry</a></p>
                        <a class="btn-outline-reg" href="https://github.com/iambestzige/gas-chemistry" target="_blank">ดาวโหลดเลย!</a>
                    </div> 
                </div>
                <div class="col-lg-6 col-xl-7">
                    <div class="image-container">
                        <img class="img-fluid" src="assets/images/details-2.png" alt="alternative" />
                    </div> 
                </div> 
            </div>
        </div> 
    </div> 


    <div id="features" class="accordion-1">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <h2 class="h2-heading">Gas Calculator</h2>
                    <p class="p-heading">หากมีคำแนะนำ หรือ พบเจอข้อผิดพลาดสามารถแจ้งได้เลยนะครับ</p>
                </div> 
            </div>   
            <div class="row">
                <div class="col-xl-5">
                    <div class="accordion" id="accordionExample">
                        <div class="accordion-item">
                            <div class="accordion-icon orange">
                                <span class="fas fa-tv"></span>
                            </div> 
                            <div class="accordion-header" id="headingOne">
                                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                                    คำตอบที่สามารถคำนวณได้!
                                </button>
                            </div>
                            <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                                <div v-if="boyleLaw">
                                    <div class="row">
                                        <div class="col-6">
                                            <span class="accordion-body fw-bold mt-2 text-dark">กฎของบอยล์</span>
                                            <div class="accordion-body">
                                                <p class="text-softgreen fw-bold">P<sub>1</sub>V<sub>1</sub>&ensp;=&ensp;P<sub>2</sub>V<sub>2</sub>&ensp;=&ensp;k</p>
                                            </div>
                                        </div>
                                        <div class="col-6">
                                            <div v-html="html.boyleLaw"></div>
                                        </div>
                                    </div>
                                </div>

                                <div v-if="charleLaw">
                                    <div class="row">
                                        <div class="col-6">
                                            <span class="accordion-body fw-bold mt-2 text-dark">กฎของชาร์ล</span>
                                            <div class="accordion-body">
                                                <p class="text-softgreen fw-bold"><sup>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub>&ensp;=&ensp;k</p>
                                            </div>
                                        </div>
                                        <div class="col-6">
                                            <div v-html="html.charleLaw"></div>
                                        </div>
                                    </div>
                                </div>

                                <div v-if="gayLussacleLaw">
                                    <div class="row">
                                        <div class="col-6">
                                            <span class="accordion-body fw-bold mt-2 text-dark">กฎของเกย์ลุสแซก</span>
                                            <div class="accordion-body">
                                                <p class="text-softgreen fw-bold">P<sub>1</sub>T<sub>1</sub>&ensp;=&ensp;P<sub>2</sub>T<sub>2</sub>&ensp;=&ensp;k</p>
                                            </div>
                                        </div>
                                        <div class="col-6">
                                            <div v-html="html.gayLussacleLaw"></div>
                                        </div>
                                    </div>
                                </div>

                                <div v-if="gasLaw">
                                    <div class="row">
                                        <div class="col-6">
                                            <span class="accordion-body fw-bold mt-2 text-dark">กฎรวมแก๊ส</span>
                                            <div class="accordion-body">
                                                <p class="text-softgreen fw-bold"><sup>P<sub>1</sub>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>P<sub>2</sub>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub>&ensp;=&ensp;k</p>
                                            </div>
                                        </div>
                                        <div class="col-6">
                                            <div v-html="html.gasLaw"></div>
                                        </div>
                                    </div>
                                </div>

                                <div v-if="canNotCal">
                                    <div class="accordion-body fw-bold mt-2">ไม่สามารถคำนวณค่าได้!</div>
                                    <div class="accordion-body">กรุณาใส่ค่าที่คุณต้องการคำนวณ</div>
                                </div>
                            </div>
                        </div>
                    </div> 
                </div> 
                <div class="col-xl-7">
                    <div class="row">
                        <div class="form-group col-sm-6 mt-2">
                            <label for="basic-url" class="label-text">P1 (ความดันเริ่มต้น) <span class="text-warning">* atm</span></label>
                            <input type="number" v-model="value.p1" class="form-control-input" placeholder="0"/>
                        </div>
                        <div class="form-group col-sm-6 mt-2">
                            <label for="basic-url" class="label-text">P2 (ความดันที่เปลี่ยนแปลง) <span class="text-warning">* atm</span></label>
                            <input type="number" v-model="value.p2" class="form-control-input" placeholder="0"/>
                        </div>
                        <div class="form-group col-sm-6 mt-2">
                            <label for="basic-url" class="label-text">V1 (ปริมาตรเริ่มต้น) <span class="text-warning">* L (ลิตร)</span></label>
                            <input type="number" v-model="value.v1" class="form-control-input" placeholder="0"/>
                        </div>
                        <div class="form-group col-sm-6 mt-2">
                            <label for="basic-url" class="label-text">V2 (ปริมาตรที่เปลี่ยนแปลง) <span class="text-warning">* L (ลิตร)</span></label>
                            <input type="number" v-model="value.v2" class="form-control-input" placeholder="0"/>
                        </div>
                        <div class="form-group col-sm-6 mt-2">
                            <label for="basic-url" class="label-text">T1 (อุณหภูมิเริ่มต้น) <span class="text-warning">* K (เคลวิน)</span></label>
                            <input type="number" v-model="value.t1" class="form-control-input" placeholder="0"/>
                        </div>
                        <div class="form-group col-sm-6 mt-2">
                            <label for="basic-url" class="label-text">T2 (อุณหภูมิที่เปลี่ยนแปลง) <span class="text-warning">* K (เคลวิน)</span></label>
                            <input type="number" v-model="value.t2" class="form-control-input" placeholder="0"/>
                        </div>

                        <div class="form-group">
                            <div class="row">
                                <div class="col-6">
                                    <button class="form-control-submit-button" @click="calSubmit">ค้นหาคำตอบของคุณเลย!</button>
                                </div>
                                <div class="col-6">
                                    <button button class="form-control-clear-button" @click="clearForm">เคลียข้อมูล!</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div> 
    </div>

    <div class="footer bg-gray">
        <img class="decoration-circles" src="assets/images/decoration-circles.png" alt="alternative" />
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <h4>หากคุณต้องการสิ่งใหม่ๆ คุณเพียงแค่ลงมือทำมัน แต่ถ้าคุณมีเงินมากพอผมพร้อมจะทำให้คุณเสมอ ขอบคุณครับ &#62; &#60; </h4>
                    <div class="social-container">
                        <span class="fa-stack">
                            <a href="https://www.facebook.com/watchara.santawee" target="_blank">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-facebook-f fa-stack-1x"></i>
                            </a>
                        </span>
                        <span class="fa-stack">
                            <a href="https://www.instagram.com/bestzige/" target="_blank">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-instagram fa-stack-1x"></i>
                            </a>
                        </span>
                        <span class="fa-stack">
                            <a href="https://www.youtube.com/channel/UCG7_XEb06GJhNdCYUdb33wA" target="_blank">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-youtube fa-stack-1x"></i>
                            </a>
                        </span>
                    </div> 
                </div> 
            </div>
        </div> 
    </div>

    <div class="copyright bg-gray">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-md-12 col-sm-12">
                    <ul class="list-unstyled li-space-lg p-small">
                        <li><a href="/">รายละเอียดบทความ</a></li>
                    </ul>
                </div> 
                <div class="col-lg-6 col-md-12 col-sm-12">
                    <p class="p-small statement">จัดทำโดย © <a href="https://www.facebook.com/watchara.santawee" target="_blank">วัชระ สันทวี</a></p>
                </div> 
            </div> 
        </div> 
    </div>

    <button id="myBtn">
        <img src="assets/images/up-arrow.png" alt="alternative" />
    </button>
</template>

<script>
export default {
    data() {
        return {
            boyleLaw: false,
            charleLaw: false,
            gayLussacleLaw: false,
            gasLaw: false,
            canNotCal: false,
            html: {
                boyleLaw: '',
                charleLaw: '',
                gayLussacleLaw: '',
                gasLaw: '',
            },
            count: {
                boyleLaw: 0,
                charleLaw: 0,
                gayLussacleLaw: 0,
                gasLaw: 0,
            },
            value: {
                p1: "",
                p2: "",
                v1: "",
                v2: "",
                t1: "",
                t2: "",
                k: "",
            }
        }
    },
    methods: {
        calSubmit() {
            // Set defalt state every time when user click submit button
            this.boyleLaw = false
            this.charleLaw = false
            this.gayLussacleLaw = false
            this.gasLaw = false
            this.canNotCal = false

            // Logic check for GasLaw's Law
            const x = true
            if(x) {
                this.gasLaw = true
                
                if(this.value.t1 != "") this.count.gasLaw = this.count.gasLaw + 1
                if(this.value.t2 != "") this.count.gasLaw = this.count.gasLaw + 1
                if(this.value.p1 != "") this.count.gasLaw = this.count.gasLaw + 1
                if(this.value.p2 != "") this.count.gasLaw = this.count.gasLaw + 1
                if(this.value.v1 != "") this.count.gasLaw = this.count.gasLaw + 1
                if(this.value.v2 != "") this.count.gasLaw = this.count.gasLaw + 1

                if(this.count.gasLaw == 5) {
                    if(this.value.p1 == "") {
                        this.html.gasLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>P<sub>2</sub>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>P<sub>1</sub>(${this.value.v1})</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;<sup>(${this.value.p2})(${this.value.v2})</sup>/<sub>(${this.value.t2})</sub></p>
                                <p>P<sub>1</sub>&ensp;=&ensp;${parseFloat((this.value.p2*this.value.v2*this.value.t1)/(this.value.t2*this.value.v1)).toFixed(4)} <span class="text-warning">atm</span></p>
                            </div>
                        `
                    } else if(this.value.p2 == "") {
                        this.html.gasLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>P<sub>2</sub>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>(${this.value.p1})(${this.value.v1})</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;<sup>P<sub>1</sub>(${this.value.v2})</sup>/<sub>(${this.value.t2})</sub></p>
                                <p>P<sub>2</sub>&ensp;=&ensp;${parseFloat((this.value.p1*this.value.v1*this.value.t2)/(this.value.t1*this.value.v2)).toFixed(4)} <span class="text-warning">atm</span></p>
                            </div>
                        `
                    } else if(this.value.t1 == "") {
                        this.html.gasLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>P<sub>2</sub>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>(${this.value.p1})(${this.value.v1})</sup>/<sub>T<sub>1</sub>&ensp;=&ensp;<sup>(${this.value.p2})(${this.value.v2})</sup>/<sub>(${this.value.t2})</sub></p>
                                <p>T<sub>1</sub>&ensp;=&ensp;${parseFloat((this.value.p1*this.value.v1*this.value.t2)/(this.value.p2*this.value.v2)).toFixed(4)} <span class="text-warning">K</span></p>
                            </div>
                        `
                    } else if(this.value.t2 == "") {
                        this.html.gasLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>P<sub>2</sub>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>(${this.value.p1})(${this.value.v1})</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;<sup>(${this.value.p2})(${this.value.v2})</sup>/<sub>T<sub>2</sub></p>
                                <p>T<sub>2</sub>&ensp;=&ensp;${parseFloat((this.value.p2*this.value.v2*this.value.t1)/(this.value.p1*this.value.v1)).toFixed(4)} <span class="text-warning">K</span></p>
                            </div>
                        `
                    } else if(this.value.v1 == "") {
                        this.html.gasLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>P<sub>2</sub>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>(${this.value.p1})V<sub>1</sub></sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;<sup>(${this.value.p2})(${this.value.v2})</sup>/<sub>(${this.value.t2})</p>
                                <p>V<sub>1</sub>&ensp;=&ensp;${parseFloat((this.value.p2*this.value.v2*this.value.t1)/(this.value.t2*this.value.p1)).toFixed(4)} <span class="text-warning">L</span></p>
                            </div>
                        `
                    } else if(this.value.v2 == "") {
                        this.html.gasLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>P<sub>2</sub>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>(${this.value.p1})(${this.value.v1}))</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;<sup>(${this.value.p2})V<sub>2</sub></sup>/<sub>(${this.value.t2})</p>
                                <p>V<sub>2</sub>&ensp;=&ensp;${parseFloat((this.value.p1*this.value.v1*this.value.t2)/(this.value.t1*this.value.p2)).toFixed(4)} <span class="text-warning">L</span></p>
                            </div>
                        `
                    }
                    this.canNotCal = false
                } else if (this.count.gasLaw == 6) {
                    this.html.gasLaw = `
                        <div class="card text-center">
                            <p><sup>P<sub>1</sub>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;k</p>
                            <p><sup>(${this.value.p1})(${this.value.v1}))</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;k</p>
                            <p>k<sub>1</sub>&ensp;=&ensp;${parseFloat((this.value.p1*this.value.v1)/this.value.t1).toFixed(4)}</p>
                            <hr>
                            <p><sup>P<sub>2</sub>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub>&ensp;=&ensp;k</p>
                            <p><sup>(${this.value.p2})(${this.value.v2}))</sup>/<sub>(${this.value.t2})</sub>&ensp;=&ensp;k</p>
                            <p>k<sub>2</sub>&ensp;=&ensp;${parseFloat((this.value.p2*this.value.v2)/this.value.t2).toFixed(4)}</p>
                        </div>
                    `
                    this.canNotCal = false
                } else {
                    if(this.value.t1 != "" && this.value.p1 != "" && this.value.v1 != "") {
                        this.html.gasLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;k</p>
                                <p><sup>(${this.value.p1})(${this.value.v1}))</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;k</p>
                                <p>k&ensp;=&ensp;${parseFloat((this.value.p1*this.value.v1)/this.value.t1).toFixed(4)}</p>
                            </div>
                        `
                        this.canNotCal = false
                    } else if(this.value.t2 != "" && this.value.p2 != "" && this.value.v2 != "") {
                        this.html.gasLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>2</sub>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub>&ensp;=&ensp;k</p>
                                <p><sup>(${this.value.p2})(${this.value.v2}))</sup>/<sub>(${this.value.t2})</sub>&ensp;=&ensp;k</p>
                                <p>k&ensp;=&ensp;${parseFloat((this.value.p2*this.value.v2)/this.value.t2).toFixed(4)}</p>
                            </div>
                        `
                        this.canNotCal = false
                    } else {
                        this.gasLaw = false
                        this.canNotCal = true
                    }
                }

                this.count.gasLaw = 0
            }

            // Logic check for Boyle's Law
            if((this.value.p1 != "" || this.value.p2 != "")
            && (this.value.v1 != "" || this.value.v2 != "")
            && (this.value.t1 == "" || this.value.t2 == "")) {
                this.boyleLaw = true
                
                if(this.value.p1 != "") this.count.boyleLaw = this.count.boyleLaw + 1
                if(this.value.p2 != "") this.count.boyleLaw = this.count.boyleLaw + 1
                if(this.value.v1 != "") this.count.boyleLaw = this.count.boyleLaw + 1
                if(this.value.v2 != "") this.count.boyleLaw = this.count.boyleLaw + 1

                if(this.count.boyleLaw == 3) {
                    if(this.value.p1 == "") {
                        this.html.boyleLaw = `
                            <div class="card text-center">
                                <p>P<sub>1</sub>V<sub>1</sub>&ensp;</sub>&ensp;=&ensp;P<sub>2</sub>V<sub>2</sub></p>
                                <p>P<sub>1</sub>(${this.value.v1})&ensp;=&ensp;(${this.value.p2})(${this.value.v2})</p>
                                <p>P<sub>1</sub>&ensp;=&ensp;${parseFloat((this.value.p2*this.value.v2)/this.value.v1).toFixed(4)} <span class="text-warning">atm</span></p>
                            </div>
                        `
                    } else if(this.value.p2 == "") {
                        this.html.boyleLaw = `
                            <div class="card text-center">
                                <p>P<sub>1</sub>V<sub>1</sub>&ensp;</sub>&ensp;=&ensp;P<sub>2</sub>V<sub>2</sub></p>
                                <p>(${this.value.p1})(${this.value.v1})&ensp;=&ensp;P<sub>2</sub>(${this.value.v2})</p>
                                <p>P<sub>2</sub>&ensp;=&ensp;${parseFloat((this.value.p1*this.value.v1)/this.value.v2).toFixed(4)} <span class="text-warning">atm</span></p>
                            </div>
                        `
                    } else if(this.value.v1 == "") {
                        this.html.boyleLaw = `
                            <div class="card text-center">
                                <p>P<sub>1</sub>V<sub>1</sub>&ensp;</sub>&ensp;=&ensp;P<sub>2</sub>V<sub>2</sub></p>
                                <p>(${this.value.p1})V<sub>1</sub>&ensp;=&ensp;(${this.value.p2})(${this.value.v2})</p>
                                <p>V<sub>1</sub>&ensp;=&ensp;${parseFloat((this.value.p2*this.value.v2)/this.value.p1).toFixed(4)} <span class="text-warning">L</span></p>
                            </div>
                        `
                    } else if(this.value.v2 == "") {
                        this.html.boyleLaw = `
                            <div class="card text-center">
                                <p>P<sub>1</sub>V<sub>1</sub>&ensp;</sub>&ensp;=&ensp;P<sub>2</sub>V<sub>2</sub></p>
                                <p>(${this.value.p1})(${this.value.v1})&ensp;=&ensp;(${this.value.p2})V<sub>2</sub></p>
                                <p>V<sub>2</sub>&ensp;=&ensp;${parseFloat((this.value.p1*this.value.v1)/this.value.p2).toFixed(4)} <span class="text-warning">L</span></p>
                            </div>
                        `
                    }
                    this.canNotCal = false
                } else if (this.count.boyleLaw == 4) {
                    this.html.boyleLaw = `
                        <div class="card text-center">
                            <p>P<sub>1</sub>V<sub>1</sub>&ensp;=&ensp;k</p>
                            <p>(${this.value.p1})(${this.value.v1})&ensp;=&ensp;k<sub>1</sub></p>
                            <p>k<sub>1</sub>&ensp;=&ensp;${this.value.p1*this.value.v1}</p>
                            <hr>
                            <p>P<sub>2</sub>V<sub>2</sub>&ensp;=&ensp;k</p>
                            <p>(${this.value.p2})(${this.value.v2})&ensp;=&ensp;k<sub>2</sub></p>
                            <p>k<sub>2</sub>&ensp;=&ensp;${this.value.p2*this.value.v2}</p>
                        </div>
                    `
                    this.canNotCal = false
                } else {
                    if(this.value.p1 != "" && this.value.v1 != "") {
                        this.html.boyleLaw = `
                            <div class="card text-center">
                                <p>P<sub>1</sub>V<sub>1</sub>&ensp;=&ensp;k</p>
                                <p>(${this.value.p1})(${this.value.v1})&ensp;=&ensp;k</p>
                                <p>k&ensp;=&ensp;${this.value.p1*this.value.v1}</p>
                            </div>
                        `
                        this.canNotCal = false
                    } else if(this.value.p2 != "" && this.value.v2 != "") {
                        this.html.boyleLaw = `
                            <div class="card text-center">
                                <p>P<sub>2</sub>V<sub>2</sub>&ensp;=&ensp;k</p>
                                <p>(${this.value.p2})(${this.value.v2})&ensp;=&ensp;k</p>
                                <p>k&ensp;=&ensp;${this.value.p2*this.value.v2}</p>
                            </div>
                        `
                        this.canNotCal = false
                    } else {
                        this.boyleLaw = false
                        this.canNotCal = true
                    }
                }

                this.count.boyleLaw = 0
            }

            // Logic check for CharleLaw's Law
            else if((this.value.t1 != "" || this.value.t2 != "")
            && (this.value.v1 != "" || this.value.v2 != "")
            && (this.value.p1 == "" || this.value.p2 == "")) {
                this.charleLaw = true
                
                if(this.value.t1 != "") this.count.charleLaw = this.count.charleLaw + 1
                if(this.value.t2 != "") this.count.charleLaw = this.count.charleLaw + 1
                if(this.value.v1 != "") this.count.charleLaw = this.count.charleLaw + 1
                if(this.value.v2 != "") this.count.charleLaw = this.count.charleLaw + 1

                if(this.count.charleLaw == 3) {
                    if(this.value.v1 == "") {
                        this.html.charleLaw = `
                            <div class="card text-center">
                                <p><sup>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>V<sub>1</sub></sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;<sup>(${this.value.v2})</sup>/<sub>(${this.value.t2})</sub></p>
                                <p>V<sub>1</sub>&ensp;=&ensp;${parseFloat((this.value.t1*this.value.v2)/this.value.t2).toFixed(4)} <span class="text-warning">L</span></p>
                            </div>
                        `
                    } else if(this.value.v2 == "") {
                        this.html.charleLaw = `
                            <div class="card text-center">
                                <p><sup>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>(${this.value.v1})</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;<sup>V<sub>2</sub></sup>/<sub>(${this.value.t2})</sub></p>
                                <p>V<sub>2</sub>&ensp;=&ensp;${parseFloat((this.value.t2*this.value.v1)/this.value.t1).toFixed(4)} <span class="text-warning">L</span></p>
                            </div>
                        `
                    } else if(this.value.t1 == "") {
                        this.html.charleLaw = `
                            <div class="card text-center">
                                <p><sup>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>(${this.value.v1})</sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>(${this.value.v2})</sup>/<sub>(${this.value.t2})</sub></p>
                                <p>T<sub>1</sub>&ensp;=&ensp;${parseFloat((this.value.t2*this.value.v1)/this.value.v2).toFixed(4)} <span class="text-warning">K</span></p>
                            </div>
                        `
                    } else if(this.value.t2 == "") {
                        this.html.charleLaw = `
                            <div class="card text-center">
                                <p><sup>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>(${this.value.v1})</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;<sup>(${this.value.v2})</sup>/<sub><sub>T<sub>2</sub></p>
                                <p>T<sub>2</sub>&ensp;=&ensp;${parseFloat((this.value.t1*this.value.v2)/this.value.v1).toFixed(4)} <span class="text-warning">K</span></p>
                            </div>
                        `
                    }
                    this.canNotCal = false
                } else if (this.count.charleLaw == 4) {
                    this.html.charleLaw = `
                        <div class="card text-center">
                            <p><sup>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;k</p>
                            <p>(${this.value.v1})</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;k</p>
                            <p>k<sub>1</sub>&ensp;=&ensp;${parseFloat(this.value.v1/this.value.t1).toFixed(4)}</p>
                            <hr>
                            <p><sup>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub>&ensp;=&ensp;k</p>
                            <p>(${this.value.v2})</sup>/<sub>(${this.value.t2})</sub>&ensp;=&ensp;k</p>
                            <p>k<sub>2</sub>&ensp;=&ensp;${parseFloat(this.value.v2/this.value.t2).toFixed(4)}</p>
                        </div>
                    `
                    this.canNotCal = false
                } else {
                    if(this.value.t1 != "" && this.value.v1 != "") {
                        this.html.charleLaw = `
                            <div class="card text-center">
                                <p><sup>V<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;k</p>
                                <p>(${this.value.v1})</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;k</p>
                                <p>k&ensp;=&ensp;${parseFloat(this.value.v1/this.value.t1).toFixed(4)}</p>
                            </div>
                        `
                        this.canNotCal = false
                    } else if(this.value.t2 != "" && this.value.v2 != "") {
                        this.html.charleLaw = `
                            <div class="card text-center">
                                <p><sup>V<sub>2</sub></sup>/<sub>T<sub>2</sub></sub>&ensp;=&ensp;k</p>
                                <p>(${this.value.v2})</sup>/<sub>(${this.value.t2})</sub>&ensp;=&ensp;k</p>
                                <p>k&ensp;=&ensp;${parseFloat(this.value.v2/this.value.t2).toFixed(4)}</p>
                            </div>
                        `
                        this.canNotCal = false
                    } else {
                        this.charleLaw = false
                        this.canNotCal = true
                    }
                }

                this.count.charleLaw = 0
            }
            
            // Logic check for GayLussacleLaw's Law
            else if((this.value.t1 != "" || this.value.t2 != "")
            && (this.value.p1 != "" || this.value.p2 != "")
            && (this.value.v1 == "" || this.value.v2 == "")) {
                this.gayLussacleLaw = true
                
                if(this.value.t1 != "") this.count.gayLussacleLaw = this.count.gayLussacleLaw + 1
                if(this.value.t2 != "") this.count.gayLussacleLaw = this.count.gayLussacleLaw + 1
                if(this.value.p1 != "") this.count.gayLussacleLaw = this.count.gayLussacleLaw + 1
                if(this.value.p2 != "") this.count.gayLussacleLaw = this.count.gayLussacleLaw + 1

                if(this.count.gayLussacleLaw == 3) {
                    if(this.value.p1 == "") {
                        this.html.gayLussacleLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>P<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>P<sub>1</sub></sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;<sup>(${this.value.p2})</sup>/<sub>(${this.value.t2})</sub></p>
                                <p>P<sub>1</sub>&ensp;=&ensp;${parseFloat((this.value.t1*this.value.p2)/this.value.t2).toFixed(4)} <span class="text-warning">atm</span></p>
                            </div>
                        `
                    } else if(this.value.p2 == "") {
                        this.html.gayLussacleLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>P<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>(${this.value.v1})</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;<sup>P<sub>2</sub></sup>/<sub>(${this.value.t2})</sub></p>
                                <p>P<sub>2</sub>&ensp;=&ensp;${parseFloat((this.value.t2*this.value.p1)/this.value.t1).toFixed(4)} <span class="text-warning">atm</span></p>
                            </div>
                        `
                    } else if(this.value.t1 == "") {
                        this.html.gayLussacleLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>P<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>(${this.value.p1})</sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>(${this.value.p2})</sup>/<sub>(${this.value.t2})</sub></p>
                                <p>T<sub>1</sub>&ensp;=&ensp;${parseFloat((this.value.t2*this.value.p1)/this.value.p2).toFixed(4)} <span class="text-warning">K</span></p>
                            </div>
                        `
                    } else if(this.value.t2 == "") {
                        this.html.gayLussacleLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;<sup>P<sub>2</sub></sup>/<sub>T<sub>2</sub></sub></p>
                                <p><sup>(${this.value.p1})</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;<sup>(${this.value.p2})</sup>/<sub><sub>T<sub>2</sub></p>
                                <p>T<sub>2</sub>&ensp;=&ensp;${parseFloat((this.value.t1*this.value.p2)/this.value.p1).toFixed(4)} <span class="text-warning">K</span></p>
                            </div>
                        `
                    }
                    this.canNotCal = false
                } else if (this.count.gayLussacleLaw == 4) {
                    this.html.gayLussacleLaw = `
                        <div class="card text-center">
                            <p><sup>P<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;k</p>
                            <p>(${this.value.p1})</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;k</p>
                            <p>k<sub>1</sub>&ensp;=&ensp;${parseFloat(this.value.p1/this.value.t1).toFixed(4)}</p>
                            <hr>
                            <p><sup>P<sub>2</sub></sup>/<sub>T<sub>2</sub></sub>&ensp;=&ensp;k</p>
                            <p>(${this.value.p2})</sup>/<sub>(${this.value.t2})</sub>&ensp;=&ensp;k</p>
                            <p>k<sub>2</sub>&ensp;=&ensp;${parseFloat(this.value.p2/this.value.t2).toFixed(4)}</p>
                        </div>
                    `
                    this.canNotCal = false
                } else {
                    if(this.value.t1 != "" && this.value.p1 != "") {
                        this.html.gayLussacleLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>1</sub></sup>/<sub>T<sub>1</sub></sub>&ensp;=&ensp;k</p>
                                <p>(${this.value.p1})</sup>/<sub>(${this.value.t1})</sub>&ensp;=&ensp;k</p>
                                <p>k&ensp;=&ensp;${parseFloat(this.value.p1/this.value.t1).toFixed(4)}</p>
                            </div>
                        `
                        this.canNotCal = false
                    } else if(this.value.t2 != "" && this.value.p2 != "") {
                        this.html.gayLussacleLaw = `
                            <div class="card text-center">
                                <p><sup>P<sub>2</sub></sup>/<sub>T<sub>2</sub></sub>&ensp;=&ensp;k</p>
                                <p>(${this.value.p2})</sup>/<sub>(${this.value.t2})</sub>&ensp;=&ensp;k</p>
                                <p>k&ensp;=&ensp;${parseFloat(this.value.p2/this.value.t2).toFixed(4)}</p>
                            </div>
                        `
                        this.canNotCal = false
                    } else {
                        this.gayLussacleLaw = false
                        this.canNotCal = true
                    }
                }

                this.count.gayLussacleLaw = 0
            }
            
        },
        clearForm() {
            // Set all data to default
            this.boyleLaw = false
            this.charleLaw = false
            this.gayLussacleLaw = false
            this.gasLaw = false
            this.canNotCal = false
            this.html.boyleLaw = ''
            this.html.charleLaw = ''
            this.html.gayLussacleLaw = ''
            this.html.gasLaw = ''
            this.count.boyleLaw = 0
            this.count.charleLaw = 0
            this.count.gayLussacleLaw = 0
            this.count.gasLaw = 0
            this.value.p1 = ""
            this.value.p2 = ""
            this.value.v1 = ""
            this.value.v2 = ""
            this.value.t1 = ""
            this.value.t2 = ""
            this.value.k = ""
        }
    }
}
</script>
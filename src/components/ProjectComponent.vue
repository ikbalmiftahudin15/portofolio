<template>
			<center><h1 class="title w-1000 rounded-full">MY PROJECT</h1></center>
    <main id="main">
	<section id="projects">
			<div class="project-tile">
		<a href="#" target="_blank"><img src="https://www.nopio.com/wp-content/uploads/2016/05/web-development.jpg"></a>
			<center><p>Jika manajemen proyek memainkan permainan, pengembangan proyek mengatur potongan-potongan sebelumnya. Pengembang proyek bekerja untuk mengatur proyek agar sukses, sementara manajer proyek memandu melalui rencana yang dibuat oleh pengembang.</p></center>
		</div>
		<div class="project-tile">
		<a href="#" target="_blank"><img src="https://www.boardinfinity.com/blog/content/images/2022/05/front-end-web-development-projects.jpg"></a>
			<center><p>Pengembang proyek meneliti aspek dari setiap proyek untuk memeriksa apakah mengikuti semua peraturan dan untuk menyelesaikan proyek tepat waktu dan di bawah anggaran. Mereka bertanggung jawab untuk mengawasi berbagai proyek untuk perusahaan mereka. Mereka mengelola proyek dan melakukan pembelian yang diperlukan.</p></center>
		</div>
		<div class="project-tile">
		<a href="#" target="_blank"><img src="https://www.eventige.com/hubfs/web-development-agency-1.png"></a>
			<center><p>Selama proses pengembangan perangkat lunak, manajer proyek dapat membantu tim mereka merancang, melaksanakan, memantau, dan menyelesaikan pekerjaan mereka untuk memastikan klien menerima produk perangkat lunak berkualitas tinggi. Manajer proyek perangkat lunak biasanya memimpin produksi perangkat lunak yang dapat disampaikan dan karyawan yang melakukan proyek tersebut.</p></center>
		</div>
		<div class="project-tile">
		<a href="#" target="_blank"><img src="https://cdn.wedevs.com/uploads/2021/04/Best-project-management-software-for-web-designers.png"></a>
			<center><p>Manajer Proyek biasanya dibayar lebih dari pengembang.</p></center>
		</div>
		<div class="project-tile">
		<a href="#" target="_blank"><img src="https://analyticsjobs.in/wp-content/uploads/2022/08/Web-Development-Projects-01-scaled-829x550.jpg"></a>
			<center><p>Sebagian besar perusahaan memerlukan pengembang proyek untuk memiliki gelar sarjana di bidang terkait, seperti bisnis atau ilmu komputer. Sangat penting untuk memiliki pengalaman kerja yang relevan, dengan persyaratan pekerjaan yang khas mulai dari 2-4 tahun di bidang terkait.</p></center>
		</div>
		<div class="project-tile">
		<a href="#" target="_blank"><img src="https://blog.udemy.com/wp-content/uploads/2022/04/Stocksy_txpb09082fbdfz200_OriginalDelivery_1109409_w1-2-scaled.jpg"></a>
			<center><p>Beralih dari peran pengembang ke peran manajer proyek dapat memerlukan perubahan pola pikir yang besar, dan Anda juga harus terlihat bagus di pasar yang kompetitif…</p></center>
		</div>
	</section>
</main>
</template>

<style>
 .title {
    color: #0a0a0a;
    font-size: 50px;
    text-transform: uppercase;
    letter-spacing: 20px;
    display: inline-block;
    margin-bottom: 0;
	padding: 90px;
    /* background: linear-gradient(
        120deg,
        #1c99fe 20.69%,
        #7644ff 50.19%,
        #fd4766 79.69%
    ); */

}

main section{
	margin:10px 10% 10px 10%;
	display:grid;
	grid-template:repeat(2,1fr)/repeat(3,1fr);
	grid-column-gap:10px;
	justify-items:center;
}
.project-tile{
	margin-bottom:100px;
	display:flex;
	flex-direction:column;
	align-items:center;
}

.project-tile p {
	font-size: 15px;
	position: relative;
}
.project-tile img{
	width: 350px;
	height: 200px;
}
main{
	padding-top:10px;
	display:flex;
	flex-direction:column;
}

main a,main a:hover,main a:active,main a:focus,main a:visited{
	text-decoration:none;
	color:#778899;
}
main section div a:hover{
	border-radius:5px;
	box-shadow:
		-5px 5px 20px,
		5px -5px 20px,
		5px 5px 20px,
		-5px -5px 20px;
}
a, a:hover, a:active, a:focus, a:visited{
	color:black;
	text-decoration:none;
}
main section div a img{
	border:solid;
	border-color:black;
	border-width:2px;
	border-radius:10px;
	height:1000px;
	width:auto;
	overflow:hidden;
}
</style>
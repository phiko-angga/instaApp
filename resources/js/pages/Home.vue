<template>
    <div>
        <div class="header-wrapper">
            <div class="search-wrapper">
                <input type="text" placeholder="Cari">
            </div>
            <div class="notifikasi-wrapper">
                <i class="fa fa-heart fa-6" aria-hidden="true"></i>
            </div>
        </div>
        <div class="reels-wrapper">
            <div class="reels-item-wrapper">
                <img src="https://www.indiewire.com/wp-content/uploads/2022/01/AP21190389554952-e1643225561835.jpg" alt="">
                <p>Sonia</p>
            </div>
            <div class="reels-item-wrapper">
                <img src="https://www.dmarge.com/wp-content/uploads/2021/01/dwayne-the-rock--480x320.jpg" alt="">
                <p>The rock</p>
            </div>
            <div class="reels-item-wrapper">
                <img src="https://www.masslive.com/resizer/kNl3qvErgJ3B0Cu-WSBWFYc1B8Q=/arc-anglerfish-arc2-prod-advancelocal/public/W5HI6Y4DINDTNP76R6CLA5IWRU.jpeg" alt="">
                <p>Delmaria...</p>
            </div>
            <div class="reels-item-wrapper">
                <img src="https://www.harleytherapy.co.uk/counselling/wp-content/uploads/16297800391_5c6e812832.jpg" alt="">
                <p>Hana</p>
            </div>
            <div class="reels-item-wrapper">
                <img src="https://cdn.hswstatic.com/gif/play/0b7f4e9b-f59c-4024-9f06-b3dc12850ab7-1920-1080.jpg" alt="">
                <p>Casie</p>
            </div>
            <div class="reels-item-wrapper">
                <img src="https://awsimages.detik.net.id/community/media/visual/2021/05/20/joy-red-velvet_43.jpeg?w=700&q=90" alt="">
                <p>Casandra</p>
            </div>
            <div class="reels-item-wrapper">
                <img src="https://www.indiewire.com/wp-content/uploads/2022/01/AP21190389554952-e1643225561835.jpg" alt="">
                <p>Sonia</p>
            </div>
        </div>

        <div class="feeds-wrapper">
            
            <div class="feeds-item">
                <div class="feeds-header">
                    <div class="feeds-header-img">
                        <img src="https://www.indiewire.com/wp-content/uploads/2022/01/AP21190389554952-e1643225561835.jpg" alt="">
                    </div>
                    
                    <div class="feeds-header-title">
                        <p>Fakta dan mitos</p>
                        <p>Audio asli</p>
                    </div>
                    
                    <div class="feeds-header-rightmenu">
                        <i class="fa fa-ellipsis-h" aria-hidden="true"></i>
                    </div>

                </div>
                <div class="feeds-video">
                    <video controls :src="video"></video>
                </div>
                <div class="feeds-footer">
                    <div class="feeds-footer-act px-2">
                        <div class="act-item">
                            <i class="fa fa-heart" aria-hidden="true"></i>
                        </div>
                        <div class="act-item">
                            <i class="fa fa-comment-o" aria-hidden="true"></i>
                        </div>
                        <div class="act-item">
                            <i class="fa fa-paper-plane-o" aria-hidden="true"></i>
                        </div>
                        <div class="act-item">
                            <i class="fa fa-bookmark-o" aria-hidden="true"></i>
                        </div>
                    </div>
                    
                    <div class="feeds-footer-content px-2">
                        <p class="feeds-like">8,789 suka</p>
                        <p class="feeds-desc">infia_fact Wali kota ....</p>
                        <p class="feeds-comment">
                            <router-link :to="{ name: 'comment' }" replace>Lihat semua komentar</router-link>
                        </p>
                        <p class="feeds-date">17 jam yang lalu</p>
                    </div>
                </div>
            </div>

        </div>

        <div class="footer-wrapper">
            <div class="footer-item">
                <i class="fa fa-home" aria-hidden="true"></i>
            </div>
            <div class="footer-item">
                <i class="fa fa-search" aria-hidden="true"></i>
            </div>
            <div class="footer-item">
                <i class="fa fa fa fa-video-camera" aria-hidden="true"></i>
            </div>
            <div class="footer-item">
                <i class="fa fa fa-paper-plane-o" aria-hidden="true"></i>
            </div>
            <div class="footer-item">
                <i class="fa fa fa fa-user-circle-o" aria-hidden="true"></i>
            </div>
        </div>
    </div>
  </template>
  
  <script>
  export default {
      
  }
  </script>
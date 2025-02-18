---
layout: post
title: /study/ M2 Medical Imaging
---

<!-- require APlayer -->
<link rel="stylesheet" href="/ipa picture/css/APlayer.min.css">
<div id="aplayer"></div>
<script src="/ipa picture/js/APlayer.min.js"></script> 


<!-- APlayer 加载参数 -->
<!-- <script type="text/javascript">
const ap = new APlayer({
    container: document.getElementById('aplayer'),
    preload: 'none',
    lrcType: 3,
    audio: {
        name: '暧昧',
        artist: '王菲',
        url: '/ipa picture/6/王菲 - 暧昧.mp3',
        cover: '/ipa picture/6/王菲 - 暧昧.jpg',
        lrc: '/ipa picture/6/王菲 - 暧昧.lrc'
    }
});
</script> -->


<!-- APlayer-full 加载参数 -->
<script type="text/javascript">
const ap = new APlayer({
    container: document.getElementById('aplayer'),
    fixed: false,
    mini: false,
    autoplay: false,
    theme: '#b7daff',
    loop: 'all', 
    order: 'list',
    preload: 'none',
    volume: 0.7,
    mutex: true,
    lrcType: 3,
    listFolded: true,
    listMaxHeight: 90,
    storageName: 'aplayer-setting',
    audio: [
        {
            name: 'Miles',
            artist: 'David Munyon',
            url: '/ipa picture/8/David Munyon - Miles.mp3',
            cover: '/ipa picture/8/David Munyon - Miles.jpg',
            lrc: '/ipa picture/8/David Munyon - Miles.lrc'
        },        
        {
            name: 'shelter',
            artist: 'hakaisu,Alys',
            url: '/ipa picture/8/hakaisu,Alys - shelter.mp3',
            cover: '/ipa picture/8/hakaisu,Alys - shelter.jpg',
            lrc: '/ipa picture/8/hakaisu,Alys - shelter.lrc'
        },
        {
            name: 'Just the Way You Are',
            artist: 'Pi Ano',
            url: '/ipa picture/8/Pi Ano - Just the Way You Are.mp3',
            cover: '/ipa picture/8/Pi Ano - Just the Way You Are.jpg',
            lrc: '/ipa picture/8/Pi Ano - Just the Way You Are.lrc'
        }
    ]
});
</script>

M2 Medical Imaging

`Lab`[MRI acquisition & image reconstruction tutorial](https://mind-inria.github.io/mri-acq-recon-book/intro.html)

## 1st Lab on MR data acquisition (sampling) ##
----

[1. Basic deterministic under-sampling](https://startadaywithasmile.github.io/ipa%20picture/M2%20Medical%20Imaging/01.LowFreq_HighFreq_Masks.html)

[2. iid Variable Density Sampling](https://startadaywithasmile.github.io/ipa%20picture/M2%20Medical%20Imaging/02.iid_VDS.html)

[3. 1D Cartesian structured VDS along parallel lines](https://startadaywithasmile.github.io/ipa%20picture/M2%20Medical%20Imaging/03.1DPhaseEncoding_VDS.html)

[4. Cartesian perodic under-sampling along parallel lines](https://startadaywithasmile.github.io/ipa%20picture/M2%20Medical%20Imaging/04.Cartesian_Regular_undersampling.html)

[5. Non-Cartesian radial under-sampling](https://startadaywithasmile.github.io/ipa%20picture/M2%20Medical%20Imaging/05.Radial_undersampling.html)

[6. Non-Cartesian spiral under-sampling](https://startadaywithasmile.github.io/ipa%20picture/M2%20Medical%20Imaging/06.Spiral_undersampling.html)

[8. Non-Cartesian 3D under-sampling](https://startadaywithasmile.github.io/ipa%20picture/M2%20Medical%20Imaging/08.3D_non-Cartesian-trajectories_adjointNUFFTrecon.html)





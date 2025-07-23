---
layout: post
title: /Document/ List document
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

## List document ##
----

{% include iframe.html src="/ipa picture/List document/Identification_de_la_réponse_électromagnétique_des_défauts_non_francs_dans_des_signaux_de_réflectométrie.pdf" %}
|rapport stage

&nbsp;

{% include iframe.html src="/ipa picture/List document/Report_on_Logistic_Regression.pdf" %}
|rapport projet

&nbsp;

{% include iframe.html src="/ipa picture/List document/rapport_projet.pdf" %}
|rapport projet

&nbsp;
{% include iframe.html src="/ipa picture/List document/rapport_stage.pdf" %}
|rapport stage

&nbsp;

{% include iframe.html src="/ipa picture/List document/Traitement_d_images_hyperspectrales.pdf" %}
|rapport

&nbsp;




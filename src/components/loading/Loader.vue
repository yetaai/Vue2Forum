<template>
<div class="outside">
    <div class="inside">
     <svg xmlns="http://www.w3.org/2000/svg" width="96" height="96">
        <linearGradient id="a" x1=".5" x2=".5" y2="1"><stop stop-color="#191919" offset="0"/><stop stop-color="#999" offset="1"/></linearGradient>
        <linearGradient id="b" x1="1" x2="0" y2="1"><stop offset="0" stop-color="#191919" stop-opacity=".9"/><stop offset="1" stop-color="#999" stop-opacity=".9"/></linearGradient>
        <linearGradient id="c" x1="1" x2="0" y1=".5" y2=".5"><stop offset="0" stop-color="#191919" stop-opacity=".8"/><stop offset="1" stop-color="#999" stop-opacity=".8"/></linearGradient>
        <linearGradient id="d" x1="1" x2="0" y1="1"><stop offset="0" stop-color="#191919" stop-opacity=".6"/><stop offset="1" stop-color="#999" stop-opacity=".6"/></linearGradient>
        <linearGradient id="e" x1=".5" x2=".5" y1="1"><stop offset="0" stop-color="#191919" stop-opacity=".5"/><stop offset="1" stop-color="#999" stop-opacity=".5"/></linearGradient>
        <linearGradient id="f" x2="1" y1="1"><stop offset="0" stop-color="#191919" stop-opacity=".4"/><stop offset="1" stop-color="#999" stop-opacity=".4"/></linearGradient>
        <linearGradient id="g" x2="1" y1=".5" y2=".5"><stop offset="0" stop-color="#191919" stop-opacity=".3"/><stop offset="1" stop-color="#999" stop-opacity=".3"/></linearGradient>
        <linearGradient id="h" x2="1" y2="1"><stop offset="0" stop-color="#191919" stop-opacity=".1"/><stop offset="1" stop-color="#999" stop-opacity=".1"/></linearGradient>
        <g transform="rotate(327.512 48 48)">
            <rect width="10" height="25" x="43" y="4" fill="url(#a)" stroke="#000" ry="5" rx="5"/>
            <rect width="25" height="10" x="61.4" y="29.6" fill="url(#b)" stroke="#000" ry="5" rx="5" transform="rotate(-45 61.44 34.56)"/>
            <rect width="25" height="10" x="67" y="43" fill="url(#c)" stroke="#000" ry="5" rx="5"/>
            <rect width="25" height="10" x="61.4" y="56.4" fill="url(#d)" stroke="#000" ry="5" rx="5" transform="rotate(45 61.44 61.44)"/>
            <rect width="10" height="25" x="43" y="67" fill="url(#e)" stroke="#000" ry="5" rx="5"/>
            <rect width="25" height="10" x="9.6" y="56.4" fill="url(#f)" stroke="#000" ry="5" rx="5" transform="rotate(-45 34.56 61.44)"/>
            <rect width="25" height="10" x="4" y="43" fill="url(#g)" stroke="#000" ry="5" rx="5"/>
            <rect width="25" height="10" x="9.6" y="29.6" fill="url(#h)" stroke="#000" ry="5" rx="5" transform="rotate(45 34.56 34.56)"/>
            <animateTransform fill="freeze" attributeName="transform" attributeType="XML" type="rotate" from="0 48 48" to="360 48 48" dur="3s" repeatCount="indefinite"/>
        </g>
     </svg>
     </div>
     </div>
</template>

<style scoped>
 .outside{
    position:relative;
    z-index:1000;
    left: 50%;
    margin-left: -50px;
  }
  .inside{
    position:absolute;
    margin-top:30px
  }
</style>

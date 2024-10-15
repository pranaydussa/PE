# parav-electronics




# Docs

- https://hackernoon.com/hosting-an-angular-application-on-amazon-s3-using-github-actions


```js
onRegionTipShow: function(e, el, code){
    console.log(logos.indexOf(code));
    if (logos.indexOf(code) != -1) {
        el.html(el.html() + '<br><img src="/images/logo/parav.png">');
    }
},
onMarkerLabelShow: function(event, label, code) {
    label.html('<img src="/images/logo/parav.png"><br>'+ label.html());                
},
// onRegionOver: function (e, code) {
//     console.log(code);
//     if (code === 'CG') {
//       $('[data-code="CG"]').css('fill', '#ccc');
//     }
// },


$('#world-map').vectorMap({
    map: 'world_mill',
    scaleColors: ['#C8EEFF', '#0071A4'],
    normalizeFunction: 'polynomial',
    hoverOpacity: 0.7,
    hoverColor: false,
    markerStyle: {
        initial: {
        fill: '#F8E23B',
        stroke: '#383f47'
        }
    },
    backgroundColor: '#9dc9fb',
    markers: [
        {latLng: [52.35, 1.17], name: 'UK'},
        {latLng: [-27.240665, 135.383063], name: 'Australia'},
        {latLng: [56.614646, -112.639088], name: 'Canada'},
        {latLng: [39.445680, -100.677982], name: 'United States'},
        {latLng: [23.885942, 45.079163], name: 'Saudi Arabia'},
        {latLng: [1.457316, 103.679985], name: 'Singapore'},
        {latLng: [46.818188, 8.227512], name: 'Switzerland'},
        {latLng: [46.227638, 2.213749], name: 'France'},
        {latLng: [50.417248, 10.356272], name: 'Germany'},
        {latLng: [50.4956754,3.3452013], name: 'Belgium'},
        {latLng: [23.259134, 54.350994], name: 'UAE'},
        {latLng: [-44.251074, 170.809232], name: 'New Zealand'},
    ],
});
```
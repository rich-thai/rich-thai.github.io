```html
<h2>Example of code</h2>

<pre>
    <div class="container">
        <div class="block two first">
            <h2>Your title</h2>
            <div class="wrap">
            <!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawcdn.githack.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_ec2093b164e840cc90050ded3bb6d819 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_ec2093b164e840cc90050ded3bb6d819" ></div>
        
</body>
<script>    
    
            var map_ec2093b164e840cc90050ded3bb6d819 = L.map(
                "map_ec2093b164e840cc90050ded3bb6d819",
                {
                    center: [43.650033, -79.396555],
                    crs: L.CRS.EPSG3857,
                    zoom: 10,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_261361a4a0b7420eab65e2ef58738f5b = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            var circle_13ac289b2ec94e94bb89f1ff51991974 = L.circle(
                [43.6475076, -79.3914841],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 72.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_13ac289b2ec94e94bb89f1ff51991974.bindTooltip(
                `<div>
                     Widmer St / Adelaide St W<br>Capacity Change: -72.0%<br> Capacity: 11<br>Net Bikes: -8.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_33f0bca5165a43939805420929b56cde = L.circle(
                [43.640722, -79.391051],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 67.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_33f0bca5165a43939805420929b56cde.bindTooltip(
                `<div>
                     Navy Wharf Ct. / Bremner Blvd.<br>Capacity Change: -67.0%<br> Capacity: 11<br>Net Bikes: -7.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d00c775d55b6496ba89d018a2d66ecfa = L.circle(
                [43.641646, -79.375308],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 65.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d00c775d55b6496ba89d018a2d66ecfa.bindTooltip(
                `<div>
                     Queens Quay / Yonge St<br>Capacity Change: -65.0%<br> Capacity: 31<br>Net Bikes: -20.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a1411ced8d114410b2d42bc7aad482ef = L.circle(
                [43.66587, -79.33443],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 59.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a1411ced8d114410b2d42bc7aad482ef.bindTooltip(
                `<div>
                     Mallon Ave / Jones Ave -SMART<br>Capacity Change: -59.0%<br> Capacity: 16<br>Net Bikes: -10.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_000e54dd01984b7588c37f7943013e7c = L.circle(
                [43.643945, -79.421189],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 57.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_000e54dd01984b7588c37f7943013e7c.bindTooltip(
                `<div>
                     Fennings St / Queen St W - SMART<br>Capacity Change: -57.0%<br> Capacity: 7<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a6b49dea577d4205a1e37e6ae6958d00 = L.circle(
                [43.6534268, -79.4512787],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 57.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a6b49dea577d4205a1e37e6ae6958d00.bindTooltip(
                `<div>
                     Dundas St W / Roncesvalles Green P - SMART<br>Capacity Change: -57.0%<br> Capacity: 12<br>Net Bikes: -7.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_4067aee6306b4027b00973a6e2e52200 = L.circle(
                [43.6720273, -79.3470557],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 55.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_4067aee6306b4027b00973a6e2e52200.bindTooltip(
                `<div>
                     Logan Ave / Bain Ave<br>Capacity Change: -55.0%<br> Capacity: 11<br>Net Bikes: -6.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f443fba8be6946f9a08af9c597a4716d = L.circle(
                [43.6476, -79.4015],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f443fba8be6946f9a08af9c597a4716d.bindTooltip(
                `<div>
                     Queen St W / Portland St<br>Capacity Change: -50.0%<br> Capacity: 22<br>Net Bikes: -11.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_335068db31a0469f952ca91570b1444d = L.circle(
                [43.646688, -79.395267],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 46.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_335068db31a0469f952ca91570b1444d.bindTooltip(
                `<div>
                     Spadina Ave / Adelaide St W<br>Capacity Change: -46.0%<br> Capacity: 15<br>Net Bikes: -7.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_bac9c8cbb8fa4f14b18dd883aa9a3169 = L.circle(
                [43.640823, -79.376265],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 45.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_bac9c8cbb8fa4f14b18dd883aa9a3169.bindTooltip(
                `<div>
                     Bay St / Queens Quay W (Ferry Terminal)<br>Capacity Change: -45.0%<br> Capacity: 23<br>Net Bikes: -10.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_26590e8b1d8440b2b053f7012254ae3a = L.circle(
                [43.6375, -79.40611111111112],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 44.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_26590e8b1d8440b2b053f7012254ae3a.bindTooltip(
                `<div>
                     Fort York Blvd / Garrison Rd<br>Capacity Change: -44.0%<br> Capacity: 15<br>Net Bikes: -7.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_0a645ddb66ea4636af77ba22943c9701 = L.circle(
                [43.6423847, -79.4240277],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 43.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_0a645ddb66ea4636af77ba22943c9701.bindTooltip(
                `<div>
                     Lisgar Park<br>Capacity Change: -43.0%<br> Capacity: 23<br>Net Bikes: -10.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_4dc1979ddbcb43a0912560419d07da94 = L.circle(
                [43.671172, -79.354704],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_4dc1979ddbcb43a0912560419d07da94.bindTooltip(
                `<div>
                     Riverdale Park North (Broadview Ave)<br>Capacity Change: -42.0%<br> Capacity: 15<br>Net Bikes: -6.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_bd7818113bd548898c3634ac66767105 = L.circle(
                [43.648437, -79.39838],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 41.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_bd7818113bd548898c3634ac66767105.bindTooltip(
                `<div>
                     Vanauley St / Queen St W - SMART<br>Capacity Change: -41.0%<br> Capacity: 9<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_fe96a85c200a4903a2b9435aeefe709b = L.circle(
                [43.6380413, -79.39783469999999],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_fe96a85c200a4903a2b9435aeefe709b.bindTooltip(
                `<div>
                     Housey St / Dan Leckie Way - SMART<br>Capacity Change: -40.0%<br> Capacity: 27<br>Net Bikes: -11.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_9f6c477bfe8743a2ba21127273358d41 = L.circle(
                [43.664736, -79.377579],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 39.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_9f6c477bfe8743a2ba21127273358d41.bindTooltip(
                `<div>
                     Jarvis St / Maitland Pl<br>Capacity Change: -39.0%<br> Capacity: 17<br>Net Bikes: -7.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_0f305f0ec4744e59bb117193163ab66b = L.circle(
                [43.660207, -79.361275],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 39.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_0f305f0ec4744e59bb117193163ab66b.bindTooltip(
                `<div>
                     Dundas St E / Regent Park Blvd<br>Capacity Change: -39.0%<br> Capacity: 19<br>Net Bikes: -8.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1f2f2c7ffe904af99572bc4bd7c24f7d = L.circle(
                [43.670318, -79.405181],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1f2f2c7ffe904af99572bc4bd7c24f7d.bindTooltip(
                `<div>
                     Kendal Ave / Spadina Rd<br>Capacity Change: -38.0%<br> Capacity: 9<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_450a1467632b403da503bc19de4857f9 = L.circle(
                [43.684566, -79.363385],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_450a1467632b403da503bc19de4857f9.bindTooltip(
                `<div>
                     Brick Works<br>Capacity Change: -38.0%<br> Capacity: 25<br>Net Bikes: -9.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_01e6d3f3de7c4209b23b7a6a85a0141f = L.circle(
                [43.657266, -79.374756],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_01e6d3f3de7c4209b23b7a6a85a0141f.bindTooltip(
                `<div>
                     Jarvis St / Dundas St E<br>Capacity Change: -38.0%<br> Capacity: 27<br>Net Bikes: -10.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c6d4cc68e2d94b68a61e3de0026339c9 = L.circle(
                [43.6436111111111, -79.4225],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 36.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c6d4cc68e2d94b68a61e3de0026339c9.bindTooltip(
                `<div>
                     Queen St W / Dovercourt Rd<br>Capacity Change: -36.0%<br> Capacity: 11<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_47166e34ab454465bc8d0265a297b0a3 = L.circle(
                [43.6576, -79.4032],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 36.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_47166e34ab454465bc8d0265a297b0a3.bindTooltip(
                `<div>
                     College St / Major St<br>Capacity Change: -36.0%<br> Capacity: 11<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_7631ff8af5344fcdb5efe40a1690f26c = L.circle(
                [43.650256, -79.36163],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 36.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_7631ff8af5344fcdb5efe40a1690f26c.bindTooltip(
                `<div>
                     Mill St / Parliament St<br>Capacity Change: -36.0%<br> Capacity: 15<br>Net Bikes: -5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_40b49005b4d54c01864520a6c0685b91 = L.circle(
                [43.643769, -79.447915],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 36.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_40b49005b4d54c01864520a6c0685b91.bindTooltip(
                `<div>
                     Garden Ave / Roncesvalles Ave<br>Capacity Change: -36.0%<br> Capacity: 18<br>Net Bikes: -6.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_37b3f491040a41f3a15af023ed29954e = L.circle(
                [43.642982, -79.399256],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 35.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_37b3f491040a41f3a15af023ed29954e.bindTooltip(
                `<div>
                     Wellington St W / Portland St<br>Capacity Change: -35.0%<br> Capacity: 11<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_19c5851b31d740e1b4d77b6ec7da1bc9 = L.circle(
                [43.6550458, -79.4034475],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 33.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_19c5851b31d740e1b4d77b6ec7da1bc9.bindTooltip(
                `<div>
                     Nassau St / Bellevue Ave<br>Capacity Change: -33.0%<br> Capacity: 15<br>Net Bikes: -5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_904a18bbb55d4967bbd4ed5ac5724634 = L.circle(
                [43.6430555555556, -79.4275],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 33.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_904a18bbb55d4967bbd4ed5ac5724634.bindTooltip(
                `<div>
                     Queen St W / Gladstone Ave<br>Capacity Change: -33.0%<br> Capacity: 15<br>Net Bikes: -5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_7c19d5a4b64743d2a0149c60410a0001 = L.circle(
                [43.6493472, -79.42668],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 32.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_7c19d5a4b64743d2a0149c60410a0001.bindTooltip(
                `<div>
                     Lisgar St / Dundas St SMART<br>Capacity Change: -32.0%<br> Capacity: 8<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d3aba4601b69439cb9db1b950a762a07 = L.circle(
                [43.6605302, -79.3787235],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 31.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d3aba4601b69439cb9db1b950a762a07.bindTooltip(
                `<div>
                     Granby St / Church St - SMART<br>Capacity Change: -31.0%<br> Capacity: 12<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_28a7b945763041c29c221653e8dfa533 = L.circle(
                [43.668427, -79.38725],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 31.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_28a7b945763041c29c221653e8dfa533.bindTooltip(
                `<div>
                     Charles St W / Balmuto St - SMART<br>Capacity Change: -31.0%<br> Capacity: 16<br>Net Bikes: -5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_19dc44cba3584f6db1a453e9c6cde6f3 = L.circle(
                [43.647992, -79.370907],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 31.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_19dc44cba3584f6db1a453e9c6cde6f3.bindTooltip(
                `<div>
                     Lower Jarvis St / The Esplanade<br>Capacity Change: -31.0%<br> Capacity: 15<br>Net Bikes: -5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_aaeb2040948043e7862417b7920e630e = L.circle(
                [43.651281, -79.411717],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_aaeb2040948043e7862417b7920e630e.bindTooltip(
                `<div>
                     Claremont St / Dundas St W<br>Capacity Change: -30.0%<br> Capacity: 13<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6a7b5db6e7d54b6c9a39e85b24a38ca1 = L.circle(
                [43.656296, -79.414663],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 30.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6a7b5db6e7d54b6c9a39e85b24a38ca1.bindTooltip(
                `<div>
                     80 Clinton St (North of College) - SMART<br>Capacity Change: -30.0%<br> Capacity: 11<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_7a4ff7c7e0c043809f664e4acfabf640 = L.circle(
                [43.6673, -79.374],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 29.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_7a4ff7c7e0c043809f664e4acfabf640.bindTooltip(
                `<div>
                     Sherbourne St / Wellesley St E<br>Capacity Change: -29.0%<br> Capacity: 31<br>Net Bikes: -9.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_dd61b74dbfe54280b1366f901723b9bd = L.circle(
                [43.638925, -79.4168659],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_dd61b74dbfe54280b1366f901723b9bd.bindTooltip(
                `<div>
                     Lynn Williams St / East Liberty St<br>Capacity Change: -28.0%<br> Capacity: 15<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_903b8b9c632b4bdbb3ffe04d16b6b836 = L.circle(
                [43.6386111111111, -79.4147222222222],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_903b8b9c632b4bdbb3ffe04d16b6b836.bindTooltip(
                `<div>
                     East Liberty St / Pirandello St<br>Capacity Change: -28.0%<br> Capacity: 19<br>Net Bikes: -5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ed4bd51eab1f4decb9c34d8dbda90733 = L.circle(
                [43.6425636, -79.3762],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ed4bd51eab1f4decb9c34d8dbda90733.bindTooltip(
                `<div>
                     12 Harbour St<br>Capacity Change: -28.0%<br> Capacity: 15<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_90fcbeda9ed64d15aeb519750f15c801 = L.circle(
                [43.6548521, -79.35397680000001],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 27.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_90fcbeda9ed64d15aeb519750f15c801.bindTooltip(
                `<div>
                     Bayview Ave / Lawren Harris Square<br>Capacity Change: -27.0%<br> Capacity: 15<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ea4dc7982da04f65bcc60e80b6bac65d = L.circle(
                [43.6563888888889, -79.4091666666667],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 27.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ea4dc7982da04f65bcc60e80b6bac65d.bindTooltip(
                `<div>
                     College St / Markham St<br>Capacity Change: -27.0%<br> Capacity: 19<br>Net Bikes: -5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ea6b3a28c7fb41d4a8fe147ca69c5b3e = L.circle(
                [43.650858, -79.387582],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ea6b3a28c7fb41d4a8fe147ca69c5b3e.bindTooltip(
                `<div>
                     Simcoe St / Queen St W<br>Capacity Change: -26.0%<br> Capacity: 27<br>Net Bikes: -7.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_eb16b05c433c4871babcce828e5e8991 = L.circle(
                [43.657991, -79.340075],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 25.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_eb16b05c433c4871babcce828e5e8991.bindTooltip(
                `<div>
                     Morse St / Eastern Ave - SMART<br>Capacity Change: -25.0%<br> Capacity: 11<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f73da3ab01d94af4a218a04d07ce92d4 = L.circle(
                [43.669576, -79.375961],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 25.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f73da3ab01d94af4a218a04d07ce92d4.bindTooltip(
                `<div>
                     Sherbourne St / Isabella St<br>Capacity Change: -25.0%<br> Capacity: 15<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_71424ca87dd4485ba5097fd48229048a = L.circle(
                [43.66834, -79.38235],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 24.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_71424ca87dd4485ba5097fd48229048a.bindTooltip(
                `<div>
                     Isabella St / Church St<br>Capacity Change: -24.0%<br> Capacity: 19<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_859d6dfb0e36485d8fcaa0fda8e9d5f6 = L.circle(
                [43.663102, -79.373181],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 24.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_859d6dfb0e36485d8fcaa0fda8e9d5f6.bindTooltip(
                `<div>
                     Sherbourne St / Carlton St (Allan Gardens)<br>Capacity Change: -24.0%<br> Capacity: 17<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1edbcf9291284a33b626f54188960b44 = L.circle(
                [43.671513, -79.408317],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 24.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1edbcf9291284a33b626f54188960b44.bindTooltip(
                `<div>
                     Kendal Ave / Bernard Ave<br>Capacity Change: -24.0%<br> Capacity: 15<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_9587ebb678464d6894be5ae027822a50 = L.circle(
                [43.6571, -79.4056],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 24.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_9587ebb678464d6894be5ae027822a50.bindTooltip(
                `<div>
                     College St / Borden St<br>Capacity Change: -24.0%<br> Capacity: 11<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ba9d8bd4152340dfbffbab206358ed35 = L.circle(
                [43.669969, -79.386532],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 24.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ba9d8bd4152340dfbffbab206358ed35.bindTooltip(
                `<div>
                     Yonge St / Bloor St<br>Capacity Change: -24.0%<br> Capacity: 14<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_86112494975640288586ad980cb3d8e3 = L.circle(
                [43.663993, -79.358534],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 23.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_86112494975640288586ad980cb3d8e3.bindTooltip(
                `<div>
                     Gerrard St E / River St<br>Capacity Change: -23.0%<br> Capacity: 11<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_aa4388c52dcf4ef6adb4c6e04dc787e4 = L.circle(
                [43.66506, -79.38357],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_aa4388c52dcf4ef6adb4c6e04dc787e4.bindTooltip(
                `<div>
                     Wellesley St E / Yonge St (Green P)<br>Capacity Change: -21.0%<br> Capacity: 17<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_809be815d7ea40d4a603b49011142ded = L.circle(
                [43.664524, -79.36793],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_809be815d7ea40d4a603b49011142ded.bindTooltip(
                `<div>
                     Carlton St / Parliament St<br>Capacity Change: -21.0%<br> Capacity: 15<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_65aff0272a5f4233ab0e809fa503ac69 = L.circle(
                [43.636611, -79.400042],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_65aff0272a5f4233ab0e809fa503ac69.bindTooltip(
                `<div>
                     Fleet St / Bathurst St<br>Capacity Change: -21.0%<br> Capacity: 19<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_b4e4b0d019324a2eb8bd1d2662263905 = L.circle(
                [43.64283, -79.38409],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_b4e4b0d019324a2eb8bd1d2662263905.bindTooltip(
                `<div>
                     Lower Simcoe St / Bremner Blvd<br>Capacity Change: -21.0%<br> Capacity: 15<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_78a54a94545e46bab2d819361ec14945 = L.circle(
                [43.645324, -79.40345],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 20.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_78a54a94545e46bab2d819361ec14945.bindTooltip(
                `<div>
                     Bathurst St / Adelaide St W<br>Capacity Change: -20.0%<br> Capacity: 25<br>Net Bikes: -5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c0928a686a674e70a3d87a3277f3be47 = L.circle(
                [43.674083, -79.368579],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 20.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c0928a686a674e70a3d87a3277f3be47.bindTooltip(
                `<div>
                     Castle Frank Station<br>Capacity Change: -20.0%<br> Capacity: 15<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_2d2f4d5b9442441682872d30bbeebf57 = L.circle(
                [43.681991, -79.329455],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 19.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_2d2f4d5b9442441682872d30bbeebf57.bindTooltip(
                `<div>
                     Danforth Ave / Lamb Ave<br>Capacity Change: -19.0%<br> Capacity: 15<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_9583831803cd419cbda3a25dd4f07c60 = L.circle(
                [43.651248, -79.357848],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 19.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_9583831803cd419cbda3a25dd4f07c60.bindTooltip(
                `<div>
                     Cherry St / Mill St<br>Capacity Change: -19.0%<br> Capacity: 15<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_be032e91b0c1496ab5c8a1aae98e7c26 = L.circle(
                [43.662712, -79.379903],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 19.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_be032e91b0c1496ab5c8a1aae98e7c26.bindTooltip(
                `<div>
                     Church St  / Wood St<br>Capacity Change: -19.0%<br> Capacity: 19<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a559ea0dbe0a45ea8f811e58c598e5b2 = L.circle(
                [43.6461, -79.3895],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 19.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a559ea0dbe0a45ea8f811e58c598e5b2.bindTooltip(
                `<div>
                     John St  / Mercer St - SMART<br>Capacity Change: -19.0%<br> Capacity: 12<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_279b80d295314c2192566d9367ad4cdf = L.circle(
                [43.654501, -79.460053],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_279b80d295314c2192566d9367ad4cdf.bindTooltip(
                `<div>
                     Parkside Dr / Bloor St W - SMART<br>Capacity Change: -18.0%<br> Capacity: 12<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_498726ab625e41588346cf8f09abf696 = L.circle(
                [43.6622222, -79.3825],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_498726ab625e41588346cf8f09abf696.bindTooltip(
                `<div>
                     Yonge St / Wood St<br>Capacity Change: -18.0%<br> Capacity: 15<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_3ae03c7a3e6748f0a33505c57581bc69 = L.circle(
                [43.6544444, -79.3711111111111],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_3ae03c7a3e6748f0a33505c57581bc69.bindTooltip(
                `<div>
                     Queen St E / George St (Moss Park)<br>Capacity Change: -18.0%<br> Capacity: 17<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_3f5d9e5083ed49ca8c6b469845222bf0 = L.circle(
                [43.640114, -79.393249],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_3f5d9e5083ed49ca8c6b469845222bf0.bindTooltip(
                `<div>
                     Spadina Ave / Fort York Blvd<br>Capacity Change: -18.0%<br> Capacity: 23<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_0cc73d97a35247e7819b53855f90078d = L.circle(
                [43.685167, -79.34962],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_0cc73d97a35247e7819b53855f90078d.bindTooltip(
                `<div>
                     Mortimer Ave / Carlaw Ave SMART<br>Capacity Change: -17.0%<br> Capacity: 12<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_19fb2bf60ef54d65980bdeb93654564f = L.circle(
                [43.656945, -79.424911],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_19fb2bf60ef54d65980bdeb93654564f.bindTooltip(
                `<div>
                     Concord Av / Dewson St<br>Capacity Change: -17.0%<br> Capacity: 17<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_b93439b881154d1cb9a0a3ad0e7c29f0 = L.circle(
                [43.671389, -79.416389],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_b93439b881154d1cb9a0a3ad0e7c29f0.bindTooltip(
                `<div>
                     Palmerston Ave / Vermont Ave<br>Capacity Change: -17.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_079d29a7c10f466b973fd680835b861a = L.circle(
                [43.63951, -79.383717],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_079d29a7c10f466b973fd680835b861a.bindTooltip(
                `<div>
                     Queens Quay W / Lower Simcoe St<br>Capacity Change: -17.0%<br> Capacity: 19<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_78c1e4b27e2540d6847fcf6ea0d983b3 = L.circle(
                [43.651678, -79.375233],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_78c1e4b27e2540d6847fcf6ea0d983b3.bindTooltip(
                `<div>
                     Church St / Lombard St<br>Capacity Change: -17.0%<br> Capacity: 17<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_0d16f48088d941748fb0b3ae446119f8 = L.circle(
                [43.66, -79.4088888888889],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_0d16f48088d941748fb0b3ae446119f8.bindTooltip(
                `<div>
                     Ulster St / Bathurst St<br>Capacity Change: -17.0%<br> Capacity: 11<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1123445c23134805876a73b9654d1085 = L.circle(
                [43.671278, -79.372127],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1123445c23134805876a73b9654d1085.bindTooltip(
                `<div>
                     Howard St / Rose Ave - SMART<br>Capacity Change: -17.0%<br> Capacity: 19<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f2902e554f264a2baa15738a75e4ad15 = L.circle(
                [43.6552778, -79.36583333333333],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f2902e554f264a2baa15738a75e4ad15.bindTooltip(
                `<div>
                     Queen St E / Berkeley St<br>Capacity Change: -16.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1ab9c3343826468e856a9d26a15ce36c = L.circle(
                [43.665801, -79.384796],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1ab9c3343826468e856a9d26a15ce36c.bindTooltip(
                `<div>
                     Yonge St / Dundonald St - SMART<br>Capacity Change: -16.0%<br> Capacity: 12<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_86d7d6ede2fd48f1b3855757f9b0603c = L.circle(
                [43.672829, -79.390592],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_86d7d6ede2fd48f1b3855757f9b0603c.bindTooltip(
                `<div>
                     Bay St / Davenport Rd<br>Capacity Change: -16.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a9df7cc95c454ddb9b1b15b5f5f9dc90 = L.circle(
                [43.656638, -79.358749],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a9df7cc95c454ddb9b1b15b5f5f9dc90.bindTooltip(
                `<div>
                     Sumach St  / Queen St E<br>Capacity Change: -16.0%<br> Capacity: 19<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_072d995a15594db6adc3e56bce7f87f3 = L.circle(
                [43.672453, -79.338259],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_072d995a15594db6adc3e56bce7f87f3.bindTooltip(
                `<div>
                     Blake St / Boultbee Ave<br>Capacity Change: -16.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_44ec2b85fae34f589738e257d82a423a = L.circle(
                [43.665867, -79.362506],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_44ec2b85fae34f589738e257d82a423a.bindTooltip(
                `<div>
                     Sumach St / Carlton St. (Riverdale Farm)<br>Capacity Change: -16.0%<br> Capacity: 14<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6d39c5320e8e4dd0b3a12dbb19b874ce = L.circle(
                [43.64534, -79.409597],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6d39c5320e8e4dd0b3a12dbb19b874ce.bindTooltip(
                `<div>
                     Niagara St / Richmond St W<br>Capacity Change: -16.0%<br> Capacity: 26<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_4fcd58c8b211410f923f10fa7b5eabd5 = L.circle(
                [43.671526, -79.44874],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_4fcd58c8b211410f923f10fa7b5eabd5.bindTooltip(
                `<div>
                     Davenport Rd / Lansdowne Ave.<br>Capacity Change: -15.0%<br> Capacity: 19<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_30e6fff20c8347b3a2f2d26a25696775 = L.circle(
                [43.657343, -79.43112],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_30e6fff20c8347b3a2f2d26a25696775.bindTooltip(
                `<div>
                     Havelock St / Dufferin Park<br>Capacity Change: -15.0%<br> Capacity: 19<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_b7a0b9107b944be191d26d76f6561825 = L.circle(
                [43.660414, -79.415646],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_b7a0b9107b944be191d26d76f6561825.bindTooltip(
                `<div>
                     Harbord St / Clinton St<br>Capacity Change: -15.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_52e265cde3a74e09ad67e6b6c7ff59fa = L.circle(
                [43.640255, -79.439223],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_52e265cde3a74e09ad67e6b6c7ff59fa.bindTooltip(
                `<div>
                     Queen St W  /  Fuller Ave - SMART<br>Capacity Change: -14.0%<br> Capacity: 16<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_7776b4cea1674d68aeb0d5623db22bcd = L.circle(
                [43.638426, -79.429142],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_7776b4cea1674d68aeb0d5623db22bcd.bindTooltip(
                `<div>
                     Tyndall Ave / King St W - SMART<br>Capacity Change: -14.0%<br> Capacity: 16<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_5dbff7d59b7c4a9e9b2480ab9e069dd1 = L.circle(
                [43.667158, -79.402761],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_5dbff7d59b7c4a9e9b2480ab9e069dd1.bindTooltip(
                `<div>
                     Madison Ave / Bloor St W<br>Capacity Change: -14.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_04b0b2c6007c47329a5d8c4599c4398c = L.circle(
                [43.681126, -79.337779],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_04b0b2c6007c47329a5d8c4599c4398c.bindTooltip(
                `<div>
                     Donlands Station<br>Capacity Change: -14.0%<br> Capacity: 11<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c7ba1ba9cf9d45f1ba3d37d2629795a1 = L.circle(
                [43.6574766, -79.373446],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c7ba1ba9cf9d45f1ba3d37d2629795a1.bindTooltip(
                `<div>
                     Dundas St E / George St<br>Capacity Change: -14.0%<br> Capacity: 25<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c5eb6ec99e2842a0a38a7771ff2e931f = L.circle(
                [43.648655, -79.367061],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c5eb6ec99e2842a0a38a7771ff2e931f.bindTooltip(
                `<div>
                     Lower Sherbourne St / The Esplanade<br>Capacity Change: -14.0%<br> Capacity: 27<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e019e10b2cb04d2c990ef2acf69d16a1 = L.circle(
                [43.68114, -79.4277],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e019e10b2cb04d2c990ef2acf69d16a1.bindTooltip(
                `<div>
                     Rushton Rd / St Clair Ave W - SMART<br>Capacity Change: -14.0%<br> Capacity: 11<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c2d3bebfeec5429a95baa610991170e7 = L.circle(
                [43.64333333333333, -79.40555555555557],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c2d3bebfeec5429a95baa610991170e7.bindTooltip(
                `<div>
                     King St W / Tecumseth St<br>Capacity Change: -14.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_7c106c76f7ac4fa38c8df6db1af1b893 = L.circle(
                [43.651145, -79.423742],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_7c106c76f7ac4fa38c8df6db1af1b893.bindTooltip(
                `<div>
                     Dovercourt Rd / Harrison St (Green P) - SMART<br>Capacity Change: -14.0%<br> Capacity: 12<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_50bc238774604a28b279e58eb9485a1a = L.circle(
                [43.653359, -79.365023],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_50bc238774604a28b279e58eb9485a1a.bindTooltip(
                `<div>
                     Berkeley St / Adelaide St E - SMART<br>Capacity Change: -14.0%<br> Capacity: 12<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_73e046dbc6da46de9a91f283b925c83c = L.circle(
                [43.7029672, -79.3979073],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_73e046dbc6da46de9a91f283b925c83c.bindTooltip(
                `<div>
                     Hillsdale Ave W / Yonge St - SMART<br>Capacity Change: -13.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_4589084850e8418aa680ea9c66690806 = L.circle(
                [43.6975969, -79.39654],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_4589084850e8418aa680ea9c66690806.bindTooltip(
                `<div>
                     Yonge St / Davisville Ave<br>Capacity Change: -13.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6cf7d638101b48da85cd7b6b96af5622 = L.circle(
                [43.690375, -79.3549427],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6cf7d638101b48da85cd7b6b96af5622.bindTooltip(
                `<div>
                     Torrens Ave / Broadview Ave<br>Capacity Change: -13.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e2256f6a98bb47f4a1cab90b89c01a56 = L.circle(
                [43.640757, -79.343144],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e2256f6a98bb47f4a1cab90b89c01a56.bindTooltip(
                `<div>
                     Cherry Beach Sports Field (55 Unwin Ave)<br>Capacity Change: -13.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_64785425dcdd4ab6a4524ed29be2818e = L.circle(
                [43.643473, -79.390477],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_64785425dcdd4ab6a4524ed29be2818e.bindTooltip(
                `<div>
                     Front St W / Blue Jays Way<br>Capacity Change: -13.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_14f993dc4bcf4924aaa1913b60051068 = L.circle(
                [43.686442, -79.313404],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_14f993dc4bcf4924aaa1913b60051068.bindTooltip(
                `<div>
                     Woodbine Subway Station - SMART<br>Capacity Change: -13.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_bc0a6fa636e84f3bada2c3721796455f = L.circle(
                [43.665278, -79.368333],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_bc0a6fa636e84f3bada2c3721796455f.bindTooltip(
                `<div>
                     Parliament St / Aberdeen Ave<br>Capacity Change: -13.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_09f00ce9dc1e438b8be22914d586d91d = L.circle(
                [43.665076, -79.341509],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_09f00ce9dc1e438b8be22914d586d91d.bindTooltip(
                `<div>
                     Carlaw Ave / Dundas St E<br>Capacity Change: -13.0%<br> Capacity: 17<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f3fe781b459a4493bd2b320e9f523f57 = L.circle(
                [43.6657049, -79.3873183],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f3fe781b459a4493bd2b320e9f523f57.bindTooltip(
                `<div>
                     St Joseph St / Bay St - SMART<br>Capacity Change: -13.0%<br> Capacity: 20<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_cf24a560dcd342d5b0cd96bb3dc32c79 = L.circle(
                [43.663912, -79.416124],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_cf24a560dcd342d5b0cd96bb3dc32c79.bindTooltip(
                `<div>
                     Bloor St W / Manning Ave - SMART<br>Capacity Change: -13.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_0efd09109c7c46739efb6950848e6e35 = L.circle(
                [43.671535, -79.379173],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_0efd09109c7c46739efb6950848e6e35.bindTooltip(
                `<div>
                     Bloor St E / Huntley St - SMART<br>Capacity Change: -12.0%<br> Capacity: 16<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_458a84e0da1a4b51a3fca131932b4dae = L.circle(
                [43.7078691, -79.39248],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_458a84e0da1a4b51a3fca131932b4dae.bindTooltip(
                `<div>
                     Eglinton Ave E / Redpath Ave<br>Capacity Change: -12.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_77ccb2749d04457c9b482b97b4d0c5e4 = L.circle(
                [43.66666667, -79.45833333333334],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_77ccb2749d04457c9b482b97b4d0c5e4.bindTooltip(
                `<div>
                     Cariboo St / Rail Path<br>Capacity Change: -12.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_206bed07aec94673881c3cbcc8a63be8 = L.circle(
                [43.645665, -79.415345],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_206bed07aec94673881c3cbcc8a63be8.bindTooltip(
                `<div>
                     Crawford St / Queen St W<br>Capacity Change: -12.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_70573c6266f54928b504e0c861ca7d01 = L.circle(
                [43.663722, -79.380288],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_70573c6266f54928b504e0c861ca7d01.bindTooltip(
                `<div>
                     Church St / Alexander St<br>Capacity Change: -12.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f3ea673f92ee4703b3aa2860a132821c = L.circle(
                [43.659777, -79.382767],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f3ea673f92ee4703b3aa2860a132821c.bindTooltip(
                `<div>
                     College Park South<br>Capacity Change: -12.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_8e23ab7013464b32ad797bbe359405b6 = L.circle(
                [43.6560758, -79.393259],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_8e23ab7013464b32ad797bbe359405b6.bindTooltip(
                `<div>
                     Baldwin St / Henry St - SMART<br>Capacity Change: -12.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d5752f5b9fc740c6823442b806bdddb7 = L.circle(
                [43.6543604, -79.4655296],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d5752f5b9fc740c6823442b806bdddb7.bindTooltip(
                `<div>
                     High Park Subway Station<br>Capacity Change: -12.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_0bab3d02fce94baa8aa492cb331ebb32 = L.circle(
                [43.6452091, -79.3960744],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_0bab3d02fce94baa8aa492cb331ebb32.bindTooltip(
                `<div>
                     457 King St. W. at Spadina<br>Capacity Change: -12.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_8bc83799e34f4971b0ed1cdb2f5f2e91 = L.circle(
                [43.6509552, -79.3707],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_8bc83799e34f4971b0ed1cdb2f5f2e91.bindTooltip(
                `<div>
                     George St / King St E<br>Capacity Change: -12.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_547e8124222445848b64d45ce1db5953 = L.circle(
                [43.65003919999999, -79.3733541],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_547e8124222445848b64d45ce1db5953.bindTooltip(
                `<div>
                     King St E / Church St<br>Capacity Change: -11.0%<br> Capacity: 14<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_da4b698929fd48e992f2b117004d12e8 = L.circle(
                [43.652473, -79.401456],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_da4b698929fd48e992f2b117004d12e8.bindTooltip(
                `<div>
                     Augusta Ave / Dundas St W<br>Capacity Change: -11.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_76227a66c4bd4a219adeff9ddfe2d911 = L.circle(
                [43.6422222, -79.41111111111111],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_76227a66c4bd4a219adeff9ddfe2d911.bindTooltip(
                `<div>
                     King St W / Stafford St<br>Capacity Change: -11.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6e1074c2811b44f7b12d58c1d048add1 = L.circle(
                [43.6672144, -79.3452697],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6e1074c2811b44f7b12d58c1d048add1.bindTooltip(
                `<div>
                     Logan Av / Gerrard St E<br>Capacity Change: -11.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1aa9a41e7cea48f498dbbe15eaf8c94b = L.circle(
                [43.676216, -79.309395],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1aa9a41e7cea48f498dbbe15eaf8c94b.bindTooltip(
                `<div>
                     Eastwood Rd / Woodbine Ave - SMART<br>Capacity Change: -11.0%<br> Capacity: 14<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d66171fd9fbd4f5f84b78db064732a3b = L.circle(
                [43.6882821, -79.4253856],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d66171fd9fbd4f5f84b78db064732a3b.bindTooltip(
                `<div>
                     Vaughan Rd /Wychwood Ave<br>Capacity Change: -11.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_50ba89ca4b6a418f8e52ecf1cf143f75 = L.circle(
                [43.6409, -79.432837],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_50ba89ca4b6a418f8e52ecf1cf143f75.bindTooltip(
                `<div>
                     Queen St W / Cowan Ave<br>Capacity Change: -11.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_648f72b2099248a493f77b5ca292134c = L.circle(
                [43.668991, -79.379385],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_648f72b2099248a493f77b5ca292134c.bindTooltip(
                `<div>
                     Jarvis St / Isabella St<br>Capacity Change: -11.0%<br> Capacity: 23<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_b430a1ac9a794d49aec30e3a668688a8 = L.circle(
                [43.685569, -79.408019],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_b430a1ac9a794d49aec30e3a668688a8.bindTooltip(
                `<div>
                     Russell Hill Rd / St Clair Ave W<br>Capacity Change: -11.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_53c74420960e433ab3d92fe4fc29ce36 = L.circle(
                [43.669232, -79.374495],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_53c74420960e433ab3d92fe4fc29ce36.bindTooltip(
                `<div>
                     Bleecker St / St James Ave<br>Capacity Change: -11.0%<br> Capacity: 20<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_fa409598aeeb4968bcc13f2f12bc8976 = L.circle(
                [43.66073, -79.47149],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_fa409598aeeb4968bcc13f2f12bc8976.bindTooltip(
                `<div>
                     Clendenan Ave / Rowland St - SMART<br>Capacity Change: -10.0%<br> Capacity: 20<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_67f3e137f0154855b46dcac2499370c9 = L.circle(
                [43.639832, -79.395954],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_67f3e137f0154855b46dcac2499370c9.bindTooltip(
                `<div>
                     Fort York  Blvd / Capreol Ct<br>Capacity Change: -10.0%<br> Capacity: 35<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_95952d1366c34229a07470675107d0c4 = L.circle(
                [43.6582, -79.3768],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_95952d1366c34229a07470675107d0c4.bindTooltip(
                `<div>
                     Gould St / Mutual St<br>Capacity Change: -10.0%<br> Capacity: 31<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1df88ee9e2d643cbaec39cc94fe95285 = L.circle(
                [43.7112153, -79.39894],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1df88ee9e2d643cbaec39cc94fe95285.bindTooltip(
                `<div>
                     Erskine Ave / Yonge St SMART<br>Capacity Change: -10.0%<br> Capacity: 16<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c616691b22f44181ba45dc5e7cddb869 = L.circle(
                [43.651238, -79.43868],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c616691b22f44181ba45dc5e7cddb869.bindTooltip(
                `<div>
                     St Clarens Ave / College St<br>Capacity Change: -10.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_99df008046a042488a48bee2509e0ed2 = L.circle(
                [43.6638889, -79.41888888888889],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_99df008046a042488a48bee2509e0ed2.bindTooltip(
                `<div>
                     Bloor St W / Christie St<br>Capacity Change: -10.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_fd36ae5c342a459a825b559ea5a5a618 = L.circle(
                [43.683378, -79.322961],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_fd36ae5c342a459a825b559ea5a5a618.bindTooltip(
                `<div>
                     Danforth Ave / Coxwell Ave<br>Capacity Change: -10.0%<br> Capacity: 15<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_eba50b9e97fd42829fd3f239a2975f77 = L.circle(
                [43.6817346, -79.4184725],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_eba50b9e97fd42829fd3f239a2975f77.bindTooltip(
                `<div>
                     Hocken Ave./Vaughan Rd.<br>Capacity Change: -10.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6e6cd178e3054e65bac1e73c5151e915 = L.circle(
                [43.661975, -79.407896],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6e6cd178e3054e65bac1e73c5151e915.bindTooltip(
                `<div>
                     Central Tech  (Harbord St)<br>Capacity Change: -10.0%<br> Capacity: 11<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_194e89b4c1a44931b9c5bcabf4c1eb21 = L.circle(
                [43.640885, -79.416379],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_194e89b4c1a44931b9c5bcabf4c1eb21.bindTooltip(
                `<div>
                     King St W / Douro St<br>Capacity Change: -10.0%<br> Capacity: 11<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e161e58cac9d4599a696c5da5da1055a = L.circle(
                [43.647497, -79.406691],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e161e58cac9d4599a696c5da5da1055a.bindTooltip(
                `<div>
                     Wolsley St / Palmerston Ave - SMART<br>Capacity Change: -10.0%<br> Capacity: 20<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ffc489c424074296ba969063565d836f = L.circle(
                [43.668153, -79.38891],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ffc489c424074296ba969063565d836f.bindTooltip(
                `<div>
                     Bay St / Charles St - SMART<br>Capacity Change: -10.0%<br> Capacity: 20<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_3e81c4ddfd8b4d3297a6144049c98e59 = L.circle(
                [43.671293, -79.380471],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_3e81c4ddfd8b4d3297a6144049c98e59.bindTooltip(
                `<div>
                     Ted Rogers Way / Bloor St E<br>Capacity Change: -9.0%<br> Capacity: 27<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_83543e0eb78e4ed6816e807c54a64b14 = L.circle(
                [43.643307, -79.402176],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_83543e0eb78e4ed6816e807c54a64b14.bindTooltip(
                `<div>
                     Stewart St / Bathurst St  - SMART<br>Capacity Change: -9.0%<br> Capacity: 16<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6a853cf87047479ca0174484b94ed37a = L.circle(
                [43.661705, -79.425734],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6a853cf87047479ca0174484b94ed37a.bindTooltip(
                `<div>
                     Ossington Ave / Bloor St W<br>Capacity Change: -9.0%<br> Capacity: 11<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d7562744d2d546ad9c30f60f36ca078f = L.circle(
                [43.687323, -79.304848],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d7562744d2d546ad9c30f60f36ca078f.bindTooltip(
                `<div>
                     Danforth Ave / Westlake Ave<br>Capacity Change: -9.0%<br> Capacity: 15<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6214e932e2d34114ba33d7ba38b6ca4f = L.circle(
                [43.690903, -79.4375028],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6214e932e2d34114ba33d7ba38b6ca4f.bindTooltip(
                `<div>
                     Alameda Ave / Vaughan Rd - SMART<br>Capacity Change: -9.0%<br> Capacity: 16<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_54f34b8c3c424cb4a11efa9462693928 = L.circle(
                [43.662862, -79.383572],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_54f34b8c3c424cb4a11efa9462693928.bindTooltip(
                `<div>
                     Yonge St / Alexander St - SMART<br>Capacity Change: -9.0%<br> Capacity: 18<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_3196ecd5f58b40abbbc96431fb06fc34 = L.circle(
                [43.65988, -79.38279],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_3196ecd5f58b40abbbc96431fb06fc34.bindTooltip(
                `<div>
                     College Park - Yonge St Entrance<br>Capacity Change: -9.0%<br> Capacity: 24<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_9e0eedcc5ddf440390d0f7be0fee8f20 = L.circle(
                [43.639179, -79.399595],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_9e0eedcc5ddf440390d0f7be0fee8f20.bindTooltip(
                `<div>
                     Bathurst St / Fort York Blvd<br>Capacity Change: -9.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d6c6012988804f00a1131b32b4048722 = L.circle(
                [43.66478, -79.45991],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d6c6012988804f00a1131b32b4048722.bindTooltip(
                `<div>
                     Dundas St W / Watkinson Ave - SMART<br>Capacity Change: -8.0%<br> Capacity: 15<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_b097779056014d309d3680926f5afc90 = L.circle(
                [43.685924, -79.376304],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_b097779056014d309d3680926f5afc90.bindTooltip(
                `<div>
                     Summerhill Ave / Maclennan Ave<br>Capacity Change: -8.0%<br> Capacity: 11<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1d15f6a87ae347809abc09d9e048856f = L.circle(
                [43.655227, -79.39201],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1d15f6a87ae347809abc09d9e048856f.bindTooltip(
                `<div>
                     D'Arcy St. /McCaul St. SMART<br>Capacity Change: -8.0%<br> Capacity: 16<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_bf8840ca1c5045daac01e994eae914c6 = L.circle(
                [43.671944, -79.387778],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_bf8840ca1c5045daac01e994eae914c6.bindTooltip(
                `<div>
                     Yonge St / Yorkville Ave<br>Capacity Change: -8.0%<br> Capacity: 17<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_b622b448c57041cea10c38615e02136f = L.circle(
                [43.6538888888889, -79.4413888888889],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_b622b448c57041cea10c38615e02136f.bindTooltip(
                `<div>
                     Lansdowne Ave / Whytock Ave<br>Capacity Change: -8.0%<br> Capacity: 15<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_8775d133c39e4ef4ac028cbb93842523 = L.circle(
                [43.681944, -79.390556],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_8775d133c39e4ef4ac028cbb93842523.bindTooltip(
                `<div>
                     Summerhill Station<br>Capacity Change: -8.0%<br> Capacity: 11<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6fd71b53282443f2a403a2094d9a884e = L.circle(
                [43.6752732, -79.3778458],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6fd71b53282443f2a403a2094d9a884e.bindTooltip(
                `<div>
                     Sherbourne St N / Elm Ave - SMART<br>Capacity Change: -8.0%<br> Capacity: 23<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_dbc796db94ea44fab3110f083dde9cf9 = L.circle(
                [43.678685, -79.297974],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_dbc796db94ea44fab3110f083dde9cf9.bindTooltip(
                `<div>
                     Southwood Dr / Kingston Rd - SMART<br>Capacity Change: -8.0%<br> Capacity: 12<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d3e350ebb7514bd6b4e8faa06484b2a7 = L.circle(
                [43.674453, -79.43439],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d3e350ebb7514bd6b4e8faa06484b2a7.bindTooltip(
                `<div>
                     Davenport Rd / Oakwood Rd - SMART<br>Capacity Change: -8.0%<br> Capacity: 12<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_fcbf3509f3d8423e86ea235db606bd84 = L.circle(
                [43.7080145, -79.39826],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_fcbf3509f3d8423e86ea235db606bd84.bindTooltip(
                `<div>
                     Roehampton Ave / Yonge St<br>Capacity Change: -8.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_765f277b16614bb4925240372d287628 = L.circle(
                [43.6452972, -79.3827914],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_765f277b16614bb4925240372d287628.bindTooltip(
                `<div>
                     Front St W / University Ave (2)<br>Capacity Change: -8.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e09b508308044e7aa0e0daf7c105df31 = L.circle(
                [43.662279, -79.334166],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e09b508308044e7aa0e0daf7c105df31.bindTooltip(
                `<div>
                     Queen St E / Larchmount Ave<br>Capacity Change: -8.0%<br> Capacity: 25<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_4bb979dcbe6e481999ffe5eb10d4743d = L.circle(
                [43.6544915, -79.422634],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_4bb979dcbe6e481999ffe5eb10d4743d.bindTooltip(
                `<div>
                     Ossington Ave / College St<br>Capacity Change: -8.0%<br> Capacity: 11<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_5f6f9577ee924fedadfae5db0518224e = L.circle(
                [43.68850459999999, -79.3940052],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_5f6f9577ee924fedadfae5db0518224e.bindTooltip(
                `<div>
                     Yonge St / St Clair Ave<br>Capacity Change: -8.0%<br> Capacity: 19<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_9540fb9e6e1043669aa8cf050fe8c484 = L.circle(
                [43.658777, -79.369596],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_9540fb9e6e1043669aa8cf050fe8c484.bindTooltip(
                `<div>
                     Seaton St / Dundas St E - SMART<br>Capacity Change: -8.0%<br> Capacity: 32<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a2d8e1fd575d4bc3bf0170b8b5e5867d = L.circle(
                [43.686829, -79.311073],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a2d8e1fd575d4bc3bf0170b8b5e5867d.bindTooltip(
                `<div>
                     Woodbine Subway Green P SMART<br>Capacity Change: -8.0%<br> Capacity: 20<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_491b8d15543b416f8a24a5ccba164886 = L.circle(
                [43.664088, -79.387095],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_491b8d15543b416f8a24a5ccba164886.bindTooltip(
                `<div>
                     Bay St / Wellesley St W<br>Capacity Change: -7.0%<br> Capacity: 51<br>Net Bikes: -4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f641a9cf0c2e4ba79123af5aa8c8e3be = L.circle(
                [43.640075, -79.414156],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f641a9cf0c2e4ba79123af5aa8c8e3be.bindTooltip(
                `<div>
                     Western Battery Rd / Pirandello St - SMART<br>Capacity Change: -7.0%<br> Capacity: 30<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6579a3a3d40649a48830e4de7372e7e5 = L.circle(
                [43.6596299, -79.4799176],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6579a3a3d40649a48830e4de7372e7e5.bindTooltip(
                `<div>
                     Runnymede Rd / Annette St - SMART<br>Capacity Change: -7.0%<br> Capacity: 15<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_24ebaa6906b14ad38ee457e520ef7d29 = L.circle(
                [43.6462574, -79.3973381],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_24ebaa6906b14ad38ee457e520ef7d29.bindTooltip(
                `<div>
                     Adelaide St W / Brant St<br>Capacity Change: -7.0%<br> Capacity: 16<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e4d4f9287b7b43a3ae97b566631f5053 = L.circle(
                [43.645215, -79.364898],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e4d4f9287b7b43a3ae97b566631f5053.bindTooltip(
                `<div>
                     Queens Quay E / Lower Sherbourne St<br>Capacity Change: -7.0%<br> Capacity: 26<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_23a568175b9741bea073b4698cc8f9c1 = L.circle(
                [43.658938, -79.383518],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_23a568175b9741bea073b4698cc8f9c1.bindTooltip(
                `<div>
                     College Park- Gerrard Entrance<br>Capacity Change: -7.0%<br> Capacity: 25<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_9b432b66690d41f99095d6ce725d6f92 = L.circle(
                [43.635492, -79.398253],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_9b432b66690d41f99095d6ce725d6f92.bindTooltip(
                `<div>
                     Bathurst St/Queens Quay(Billy Bishop Airport)<br>Capacity Change: -7.0%<br> Capacity: 34<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_67baf95e275646c88a926f2195f414f4 = L.circle(
                [43.67, -79.42083333333333],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_67baf95e275646c88a926f2195f414f4.bindTooltip(
                `<div>
                     Yarmouth Rd / Christie St<br>Capacity Change: -7.0%<br> Capacity: 11<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_df1417ec0a7c4292ad0f4aa3649e4129 = L.circle(
                [43.646677, -79.442741],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_df1417ec0a7c4292ad0f4aa3649e4129.bindTooltip(
                `<div>
                     Wright / Sorauren (Sorauren Park) - SMART<br>Capacity Change: -7.0%<br> Capacity: 18<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_0d8d2b2af29b4aee8a9bcb33009e3714 = L.circle(
                [43.68, -79.391111],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_0d8d2b2af29b4aee8a9bcb33009e3714.bindTooltip(
                `<div>
                     Marlborough Ave / Yonge St<br>Capacity Change: -7.0%<br> Capacity: 23<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_bd3ef2bf09da440ca33999ab264fa33f = L.circle(
                [43.67851, -79.44215],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_bd3ef2bf09da440ca33999ab264fa33f.bindTooltip(
                `<div>
                     Westmount Ave / St Clair Ave W - SMART<br>Capacity Change: -7.0%<br> Capacity: 14<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a042c63576f84155a94b8bafea35e72d = L.circle(
                [43.689293, -79.295895],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a042c63576f84155a94b8bafea35e72d.bindTooltip(
                `<div>
                     Trent Ave / Danforth Ave - SMART<br>Capacity Change: -7.0%<br> Capacity: 23<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_33a7ad74477148eebe45dc89bce73f0c = L.circle(
                [43.656333, -79.379114],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_33a7ad74477148eebe45dc89bce73f0c.bindTooltip(
                `<div>
                     Dundas St E / Victoria St<br>Capacity Change: -7.0%<br> Capacity: 39<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e2ca70f1ccfc4da19dcf1144244d286e = L.circle(
                [43.67072, -79.42677],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e2ca70f1ccfc4da19dcf1144244d286e.bindTooltip(
                `<div>
                     Shaw St / Dupont St<br>Capacity Change: -7.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1fbfd48ff18d45f6aea4d91d4782ee1e = L.circle(
                [43.70942, -79.39139],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1fbfd48ff18d45f6aea4d91d4782ee1e.bindTooltip(
                `<div>
                     Roehampton Ave / Mount Pleasant Rd<br>Capacity Change: -7.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_04705d977bb345a6b5cd8d7fd311921a = L.circle(
                [43.694341, -79.291416],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_04705d977bb345a6b5cd8d7fd311921a.bindTooltip(
                `<div>
                     Dentonia Park<br>Capacity Change: -7.0%<br> Capacity: 23<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a96e2f8a02ee476abe4c493a3df3a2a4 = L.circle(
                [43.645572, -79.39399],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a96e2f8a02ee476abe4c493a3df3a2a4.bindTooltip(
                `<div>
                     King St W / Charlotte St (West)<br>Capacity Change: -7.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f2d5f66285a244e4b0eedeb51c9a67cf = L.circle(
                [43.634896, -79.467763],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f2d5f66285a244e4b0eedeb51c9a67cf.bindTooltip(
                `<div>
                     Lakeshore Blvd W / Windermere Ave<br>Capacity Change: -7.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_eddf4b270bf14324a3d97ae96a180d7a = L.circle(
                [43.674444, -79.414722],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_eddf4b270bf14324a3d97ae96a180d7a.bindTooltip(
                `<div>
                     Bridgeman Ave / Bathurst St<br>Capacity Change: -6.0%<br> Capacity: 15<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_06fbd821dccf483ab066d87e7291b292 = L.circle(
                [43.6753188, -79.3462789],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_06fbd821dccf483ab066d87e7291b292.bindTooltip(
                `<div>
                     Carlaw Ave / Strathcona Ave<br>Capacity Change: -6.0%<br> Capacity: 15<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e88a248844b34a1789945e91b0ebf606 = L.circle(
                [43.6809164, -79.4229684],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e88a248844b34a1789945e91b0ebf606.bindTooltip(
                `<div>
                     Wychwood Ave / Benson Ave - SMART<br>Capacity Change: -6.0%<br> Capacity: 16<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1228c1182d644e57b8e2c9788ea1d379 = L.circle(
                [43.667266, -79.443946],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1228c1182d644e57b8e2c9788ea1d379.bindTooltip(
                `<div>
                     Dupont St / Emerson Ave SMART<br>Capacity Change: -6.0%<br> Capacity: 16<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_7479be021236419e890a2c264f518863 = L.circle(
                [43.680095, -79.291714],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_7479be021236419e890a2c264f518863.bindTooltip(
                `<div>
                     Kingston Rd / Beech Ave - SMART<br>Capacity Change: -6.0%<br> Capacity: 15<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d9de2acf6bba400c818f5aa8d2198fed = L.circle(
                [43.713524, -79.400162],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d9de2acf6bba400c818f5aa8d2198fed.bindTooltip(
                `<div>
                     Briar Hill Ave / Yonge St - SMART<br>Capacity Change: -6.0%<br> Capacity: 16<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_5298627111364425b88bd25d49bd504c = L.circle(
                [43.672571, -79.289],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_5298627111364425b88bd25d49bd504c.bindTooltip(
                `<div>
                     Queen St. E / Spruce Hill Rd.<br>Capacity Change: -6.0%<br> Capacity: 15<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ba47f00abed64d2984ce28dd14441c07 = L.circle(
                [43.654565, -79.384679],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ba47f00abed64d2984ce28dd14441c07.bindTooltip(
                `<div>
                     Foster Pl / Elizabeth St - SMART<br>Capacity Change: -6.0%<br> Capacity: 18<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_8eb03554f2bb4f46bc4689dc3415ad8d = L.circle(
                [43.63796, -79.387502],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_8eb03554f2bb4f46bc4689dc3415ad8d.bindTooltip(
                `<div>
                     HTO Park (Queens Quay W)<br>Capacity Change: -6.0%<br> Capacity: 27<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_dfcb5d45a8ee4a1fa981e39669cbc634 = L.circle(
                [43.6308933, -79.4722622],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_dfcb5d45a8ee4a1fa981e39669cbc634.bindTooltip(
                `<div>
                     Humber Bay Shores Park East<br>Capacity Change: -6.0%<br> Capacity: 23<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ab9389548cbc43c78419c9efea855caa = L.circle(
                [43.6535, -79.354068],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ab9389548cbc43c78419c9efea855caa.bindTooltip(
                `<div>
                     Front St E / Bayview Avenue<br>Capacity Change: -6.0%<br> Capacity: 22<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_04bd25892aa04c9493f7ef9be5bf71e6 = L.circle(
                [43.670206, -79.402643],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_04bd25892aa04c9493f7ef9be5bf71e6.bindTooltip(
                `<div>
                     541 Huron St - SMART<br>Capacity Change: -6.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_59174e67872a46f7b86810db75a33303 = L.circle(
                [43.646144, -79.377962],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_59174e67872a46f7b86810db75a33303.bindTooltip(
                `<div>
                     Front St W / Yonge St (Hockey Hall of Fame)<br>Capacity Change: -6.0%<br> Capacity: 47<br>Net Bikes: -3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_2d609faa01be4d739f1aab853a835ec2 = L.circle(
                [43.6555556, -79.43361111111112],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_2d609faa01be4d739f1aab853a835ec2.bindTooltip(
                `<div>
                     Dufferin St / Sylvan Av (Dufferin Grove Park)<br>Capacity Change: -6.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_49ba924ae561498b8f48ed486ab61f0a = L.circle(
                [43.690537, -79.341307],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_49ba924ae561498b8f48ed486ab61f0a.bindTooltip(
                `<div>
                     Cosburn Ave / Donlands Ave<br>Capacity Change: -6.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ab386a44e3884399ad42c786d4bb50d8 = L.circle(
                [43.652823, -79.393388],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ab386a44e3884399ad42c786d4bb50d8.bindTooltip(
                `<div>
                     Beverley  St / Dundas St W<br>Capacity Change: -6.0%<br> Capacity: 31<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f8bb4b33b9904177b3ee6be172f12cb8 = L.circle(
                [43.63985, -79.43703],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f8bb4b33b9904177b3ee6be172f12cb8.bindTooltip(
                `<div>
                     Jameson Ave / Queen St W<br>Capacity Change: -6.0%<br> Capacity: 27<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_958f8c6633894c2d92131ca067c3577b = L.circle(
                [43.64116, -79.37979],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_958f8c6633894c2d92131ca067c3577b.bindTooltip(
                `<div>
                     York St / Harbour St<br>Capacity Change: -6.0%<br> Capacity: 39<br>Net Bikes: -2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_5037e63b18de477c8526b22dcbcdde1a = L.circle(
                [43.6575, -79.4502777777778],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_5037e63b18de477c8526b22dcbcdde1a.bindTooltip(
                `<div>
                     Bloor GO / UP Station (West Toronto Railpath)<br>Capacity Change: -6.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1643759a2a464e578589d155f74c49cf = L.circle(
                [43.70567, -79.310554],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1643759a2a464e578589d155f74c49cf.bindTooltip(
                `<div>
                     St Columba Pl / St Clair Ave E - SMART<br>Capacity Change: -6.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_b52196f80b694f98ac51ac25e791f821 = L.circle(
                [43.63732, -79.489083],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_b52196f80b694f98ac51ac25e791f821.bindTooltip(
                `<div>
                     Berry Rd / Bell Manor Dr<br>Capacity Change: -6.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_3e8a81a1d981406f898e3c072b6bcc85 = L.circle(
                [43.651318, -79.36023],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_3e8a81a1d981406f898e3c072b6bcc85.bindTooltip(
                `<div>
                     Trinity St /Front St E<br>Capacity Change: -5.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_af415d6079f94946906b08c5f9d83a33 = L.circle(
                [43.6615467, -79.498398],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_af415d6079f94946906b08c5f9d83a33.bindTooltip(
                `<div>
                     Florence Gell Park<br>Capacity Change: -5.0%<br> Capacity: 15<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c8b080268ceb4580b265ed79e141f54b = L.circle(
                [43.6910667, -79.39535],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c8b080268ceb4580b265ed79e141f54b.bindTooltip(
                `<div>
                     Lawton Blvd / Yonge St<br>Capacity Change: -5.0%<br> Capacity: 15<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_b3cd1468cc954478ac7090e46672560a = L.circle(
                [43.684758, -79.316767],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_b3cd1468cc954478ac7090e46672560a.bindTooltip(
                `<div>
                     Danforth Ave / Aldridge Ave<br>Capacity Change: -5.0%<br> Capacity: 11<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_13bb5e80fcdc4df8802f2bd6b9a8e893 = L.circle(
                [43.655, -79.418889],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_13bb5e80fcdc4df8802f2bd6b9a8e893.bindTooltip(
                `<div>
                     College St / Crawford St<br>Capacity Change: -5.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f4fa7209912e468eaadbedfd5c82df47 = L.circle(
                [43.646552, -79.406468],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f4fa7209912e468eaadbedfd5c82df47.bindTooltip(
                `<div>
                     Tecumseth St / Queen St W - SMART<br>Capacity Change: -5.0%<br> Capacity: 9<br>Net Bikes: -0.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_973f7192d20b4d15937cb0a434f86725 = L.circle(
                [43.649709, -79.364184],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_973f7192d20b4d15937cb0a434f86725.bindTooltip(
                `<div>
                     The Esplanade / Hahn Pl - SMART<br>Capacity Change: -5.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_3dd752e2c9d94447817b6e63ed0b4203 = L.circle(
                [43.64656, -79.375274],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_3dd752e2c9d94447817b6e63ed0b4203.bindTooltip(
                `<div>
                     Scott St / The Esplanade<br>Capacity Change: -5.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_97dc4cc12eda454eb628bcf4e1b652c6 = L.circle(
                [43.6691099, -79.38551],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_97dc4cc12eda454eb628bcf4e1b652c6.bindTooltip(
                `<div>
                     20 Charles St E<br>Capacity Change: -5.0%<br> Capacity: 23<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_699fbd7772b5400487ee3ed1431afc61 = L.circle(
                [43.64407, -79.3929],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_699fbd7772b5400487ee3ed1431afc61.bindTooltip(
                `<div>
                     Clarence Square<br>Capacity Change: -5.0%<br> Capacity: 23<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ca982a32427b49408cc095316cee61b6 = L.circle(
                [43.654905, -79.398448],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ca982a32427b49408cc095316cee61b6.bindTooltip(
                `<div>
                     Baldwin Ave / Spadina Ave - SMART<br>Capacity Change: -5.0%<br> Capacity: 20<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_96b86d077e3a4267ad027be5a2ff70eb = L.circle(
                [43.63855, -79.46693],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_96b86d077e3a4267ad027be5a2ff70eb.bindTooltip(
                `<div>
                     Ellis Ave / The Queensway<br>Capacity Change: -5.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_0d508e9b8cb64268bb449bdaab875a52 = L.circle(
                [43.663912, -79.327987],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_0d508e9b8cb64268bb449bdaab875a52.bindTooltip(
                `<div>
                     Queen St E / Alton Av<br>Capacity Change: -5.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a9688811c142408197c6d20e547c952f = L.circle(
                [43.6940155, -79.2889842],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a9688811c142408197c6d20e547c952f.bindTooltip(
                `<div>
                     Victoria Park Subway Station - SMART<br>Capacity Change: -5.0%<br> Capacity: 20<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_15b956253de04024a0bc26a53ddb7707 = L.circle(
                [43.66908, -79.3149],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_15b956253de04024a0bc26a53ddb7707.bindTooltip(
                `<div>
                     Orchard Park<br>Capacity Change: -5.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6c5cfc696aa04a59a3abe8b34471debe = L.circle(
                [43.684261, -79.299332],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6c5cfc696aa04a59a3abe8b34471debe.bindTooltip(
                `<div>
                     Gerrard St E / Ted Reeve Dr<br>Capacity Change: -5.0%<br> Capacity: 22<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_7c6d54c71e8b4b09a3e5e72037f69d79 = L.circle(
                [43.635932, -79.465083],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_7c6d54c71e8b4b09a3e5e72037f69d79.bindTooltip(
                `<div>
                     Lakeshore Blvd W / Ellis Ave<br>Capacity Change: -5.0%<br> Capacity: 19<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_044356f1233d410f9eeda350fc338a24 = L.circle(
                [43.65917, -79.46997],
                {"bubblingMouseEvents": true, "color": "#FF0000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#FF0000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_044356f1233d410f9eeda350fc338a24.bindTooltip(
                `<div>
                     Humberside Grounds - SMART<br>Capacity Change: -5.0%<br> Capacity: 20<br>Net Bikes: -1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_69274e15bb8f468e9a3e7bb1f3fd4ccb = L.circle(
                [43.711751, -79.378615],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_69274e15bb8f468e9a3e7bb1f3fd4ccb.bindTooltip(
                `<div>
                     Roehampton St / Bayview Ave - SMART<br>Capacity Change: 5.0%<br> Capacity: 31<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_0339b3f271234866a242f52a4f5ea45c = L.circle(
                [43.667023, -79.401805],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_0339b3f271234866a242f52a4f5ea45c.bindTooltip(
                `<div>
                     Bloor St W / Huron St<br>Capacity Change: 5.0%<br> Capacity: 25<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f8b5513c42b9403380d5e671594cfeb1 = L.circle(
                [43.657424, -79.381019],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f8b5513c42b9403380d5e671594cfeb1.bindTooltip(
                `<div>
                     Gould St / Yonge St (Ryerson University)<br>Capacity Change: 5.0%<br> Capacity: 23<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e5ee63830a8f4ed18450f0103210b355 = L.circle(
                [43.668496, -79.485426],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e5ee63830a8f4ed18450f0103210b355.bindTooltip(
                `<div>
                     St Clair Ave W / Castleton Ave - SMART<br>Capacity Change: 5.0%<br> Capacity: 19<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6ceb2342e39d47dcbcf60180a43635f2 = L.circle(
                [43.663808, -79.410491],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6ceb2342e39d47dcbcf60180a43635f2.bindTooltip(
                `<div>
                     Bathurst St / Lennox St<br>Capacity Change: 5.0%<br> Capacity: 19<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_51cd015cc2c044839c80aed0392317cf = L.circle(
                [43.6535269, -79.4650569],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_51cd015cc2c044839c80aed0392317cf.bindTooltip(
                `<div>
                     Bloor St W / High Park Ave (High Park)<br>Capacity Change: 5.0%<br> Capacity: 19<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_0ad76305e5924d7b89a321ef44f40bde = L.circle(
                [43.656927, -79.378497],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_0ad76305e5924d7b89a321ef44f40bde.bindTooltip(
                `<div>
                     111 Bond St (North of Dundas St E)  - SMART<br>Capacity Change: 5.0%<br> Capacity: 16<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_38872e3505ad413085dcc692cd9f66ea = L.circle(
                [43.66189, -79.42679],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_38872e3505ad413085dcc692cd9f66ea.bindTooltip(
                `<div>
                     Concord Ave / Bloor St W - SMART<br>Capacity Change: 5.0%<br> Capacity: 15<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_2a5d7ff8bd604bc48e2298dfb8251798 = L.circle(
                [43.732975, -79.40401],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_2a5d7ff8bd604bc48e2298dfb8251798.bindTooltip(
                `<div>
                     Teddington Park Ave - SMART<br>Capacity Change: 6.0%<br> Capacity: 15<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c8e9d0bfb75546a5809779f7fd699628 = L.circle(
                [43.6653032, -79.4701178],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c8e9d0bfb75546a5809779f7fd699628.bindTooltip(
                `<div>
                     High Park Ave / Dundas St W<br>Capacity Change: 6.0%<br> Capacity: 15<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_cddca8267c9b4a179b4889d739c6d520 = L.circle(
                [43.671827, -79.371849],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_cddca8267c9b4a179b4889d739c6d520.bindTooltip(
                `<div>
                     Parliament St / Bloor St E<br>Capacity Change: 6.0%<br> Capacity: 15<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6182e3045b9a435c97e983e24b634295 = L.circle(
                [43.660087, -79.385655],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6182e3045b9a435c97e983e24b634295.bindTooltip(
                `<div>
                     Bay St / College St (West Side) - SMART<br>Capacity Change: 6.0%<br> Capacity: 12<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d671b520a4eb4ca7895bdf6ddd268c47 = L.circle(
                [43.654074, -79.398115],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d671b520a4eb4ca7895bdf6ddd268c47.bindTooltip(
                `<div>
                     D'Arcy St / Spadina Ave - SMART<br>Capacity Change: 6.0%<br> Capacity: 17<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c4560d9b884e4917aa351a1dec690d72 = L.circle(
                [43.661324, -79.449534],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c4560d9b884e4917aa351a1dec690d72.bindTooltip(
                `<div>
                     Wallace Ave / Symington Ave - SMART<br>Capacity Change: 6.0%<br> Capacity: 12<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_aff1e2265b664263b41d027c26a599f8 = L.circle(
                [43.6366666666667, -79.4197222222222],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_aff1e2265b664263b41d027c26a599f8.bindTooltip(
                `<div>
                     Exhibition GO (Atlantic Ave)<br>Capacity Change: 6.0%<br> Capacity: 23<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_459ca4db7c314c6eb612cfce689a2ebb = L.circle(
                [43.6458569, -79.3853654],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_459ca4db7c314c6eb612cfce689a2ebb.bindTooltip(
                `<div>
                     Simcoe St / Wellington St South<br>Capacity Change: 6.0%<br> Capacity: 27<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e96becee2b86446c82b3b47100a0d649 = L.circle(
                [43.665656, -79.352055],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e96becee2b86446c82b3b47100a0d649.bindTooltip(
                `<div>
                     Gerrard St E / Broadview - SMART<br>Capacity Change: 7.0%<br> Capacity: 18<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a8c80799d4024c50bbbe377808b2121d = L.circle(
                [43.64595, -79.378761],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a8c80799d4024c50bbbe377808b2121d.bindTooltip(
                `<div>
                     Front St W / Bay St (South Side)<br>Capacity Change: 7.0%<br> Capacity: 19<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1dd8d6c58c0e41c79fe32377ababcde4 = L.circle(
                [43.65158, -79.38655],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1dd8d6c58c0e41c79fe32377ababcde4.bindTooltip(
                `<div>
                     University Ave / Queen St W<br>Capacity Change: 7.0%<br> Capacity: 23<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1afa0940c9874b84bcb22ab2675504d5 = L.circle(
                [43.67142, -79.445947],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1afa0940c9874b84bcb22ab2675504d5.bindTooltip(
                `<div>
                     Primrose Ave / Davenport Rd - SMART<br>Capacity Change: 7.0%<br> Capacity: 15<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e80b8671f868410eafedac5f57dee5ac = L.circle(
                [43.65294, -79.3783],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e80b8671f868410eafedac5f57dee5ac.bindTooltip(
                `<div>
                     Victoria St / Queen St E<br>Capacity Change: 8.0%<br> Capacity: 23<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_985f437c85fb46a0b29ce5394a8e9edf = L.circle(
                [43.656729, -79.382736],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_985f437c85fb46a0b29ce5394a8e9edf.bindTooltip(
                `<div>
                     Edward St / Yonge St<br>Capacity Change: 8.0%<br> Capacity: 23<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_9e18f1c9e2384152a0a4f10ef4655ae4 = L.circle(
                [43.671685, -79.325176],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_9e18f1c9e2384152a0a4f10ef4655ae4.bindTooltip(
                `<div>
                     Highfield Rd / Gerrard St E - SMART<br>Capacity Change: 8.0%<br> Capacity: 19<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_805214afc2694b28947d73b4a2b1be17 = L.circle(
                [43.641529, -79.386741],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_805214afc2694b28947d73b4a2b1be17.bindTooltip(
                `<div>
                     Bremner Blvd / Rees St<br>Capacity Change: 8.0%<br> Capacity: 23<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d3ec6867066c48b2b920614655f490cc = L.circle(
                [43.639444, -79.423611],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d3ec6867066c48b2b920614655f490cc.bindTooltip(
                `<div>
                     King St W / Joe Shuster Way<br>Capacity Change: 8.0%<br> Capacity: 15<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f2e598b7742f4abba9186a9f0ba767d3 = L.circle(
                [43.660439, -79.385525],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f2e598b7742f4abba9186a9f0ba767d3.bindTooltip(
                `<div>
                     Bay St / College St (East Side)<br>Capacity Change: 8.0%<br> Capacity: 11<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_3e531b0f4fc74ecf868c19afb3dbc0af = L.circle(
                [43.668633, -79.291162],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_3e531b0f4fc74ecf868c19afb3dbc0af.bindTooltip(
                `<div>
                     Hubbard Blvd. / Glen Manor Dr.<br>Capacity Change: 8.0%<br> Capacity: 14<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_bb4c889c216049d596b5bb0aa98a6e76 = L.circle(
                [43.640634, -79.435841],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_bb4c889c216049d596b5bb0aa98a6e76.bindTooltip(
                `<div>
                     Queen St W / Close Ave<br>Capacity Change: 8.0%<br> Capacity: 23<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ad70372d96fd40a0b89c432db8add680 = L.circle(
                [43.645859, -79.38783],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ad70372d96fd40a0b89c432db8add680.bindTooltip(
                `<div>
                     Metro Hall Plaza<br>Capacity Change: 9.0%<br> Capacity: 27<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_773f7c9d05844aa984de32b1b014b6a9 = L.circle(
                [43.657192, -79.452559],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_773f7c9d05844aa984de32b1b014b6a9.bindTooltip(
                `<div>
                     Dundas St W / Edna Ave<br>Capacity Change: 9.0%<br> Capacity: 15<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d593d5f17eb34bee82d1c42a623ce9bd = L.circle(
                [43.6481303, -79.38632],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d593d5f17eb34bee82d1c42a623ce9bd.bindTooltip(
                `<div>
                     Simcoe St / Adelaide St W<br>Capacity Change: 9.0%<br> Capacity: 20<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6c3f84fd70754cc0920fbb34854e9d6d = L.circle(
                [43.6712581, -79.376367],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6c3f84fd70754cc0920fbb34854e9d6d.bindTooltip(
                `<div>
                     Howard St / Sherbourne St<br>Capacity Change: 9.0%<br> Capacity: 15<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_32cb3ecbfdc54c80bf73f79c8d66eff1 = L.circle(
                [43.645062, -79.397345],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_32cb3ecbfdc54c80bf73f79c8d66eff1.bindTooltip(
                `<div>
                     King St W / Brant St<br>Capacity Change: 9.0%<br> Capacity: 23<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_44b5c83703bd4e21a1baa4c46fa8bc07 = L.circle(
                [43.638333, -79.419722],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_44b5c83703bd4e21a1baa4c46fa8bc07.bindTooltip(
                `<div>
                     Hanna Ave / Liberty St<br>Capacity Change: 9.0%<br> Capacity: 15<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f69e8aba2ec24285941bf319979e13a0 = L.circle(
                [43.633537, -79.437461],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f69e8aba2ec24285941bf319979e13a0.bindTooltip(
                `<div>
                     Marilyn Bell Park Tennis Court<br>Capacity Change: 10.0%<br> Capacity: 27<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c3b3c79a043c4651a76013ddb2129d8b = L.circle(
                [43.651667, -79.384167],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c3b3c79a043c4651a76013ddb2129d8b.bindTooltip(
                `<div>
                     Queen St W / York St (City Hall)<br>Capacity Change: 10.0%<br> Capacity: 31<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ae2068c460084aa9a6cc30f44b6b3624 = L.circle(
                [43.6356551, -79.4184785],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ae2068c460084aa9a6cc30f44b6b3624.bindTooltip(
                `<div>
                     Exhibition GO Station<br>Capacity Change: 10.0%<br> Capacity: 15<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_445f62bb89a649969a28fc1e34c82017 = L.circle(
                [43.653264, -79.382458],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_445f62bb89a649969a28fc1e34c82017.bindTooltip(
                `<div>
                     Bay St / Albert St<br>Capacity Change: 10.0%<br> Capacity: 35<br>Net Bikes: 4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_7e33bfdc7115410da8b0723dc30327fe = L.circle(
                [43.65246, -79.413528],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_7e33bfdc7115410da8b0723dc30327fe.bindTooltip(
                `<div>
                     Bellwoods Ave / Treford Pl - SMART<br>Capacity Change: 10.0%<br> Capacity: 20<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_8d71727c308448dbbeca13b68296f7a2 = L.circle(
                [43.688325, -79.300463],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_8d71727c308448dbbeca13b68296f7a2.bindTooltip(
                `<div>
                     Danforth Ave / Barrington Ave<br>Capacity Change: 10.0%<br> Capacity: 15<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_8ba2496dc5c44d439a7cb06a4b842ebe = L.circle(
                [43.652686, -79.358395],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_8ba2496dc5c44d439a7cb06a4b842ebe.bindTooltip(
                `<div>
                     Front St E / Cherry St<br>Capacity Change: 10.0%<br> Capacity: 15<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_67d0dcfd92e64f90adc36cbe3f884b11 = L.circle(
                [43.651118, -79.369411],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_67d0dcfd92e64f90adc36cbe3f884b11.bindTooltip(
                `<div>
                     Frederick St / King St E<br>Capacity Change: 11.0%<br> Capacity: 23<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e3ad632197f5473b955a5b30f598e610 = L.circle(
                [43.668561, -79.394403],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e3ad632197f5473b955a5b30f598e610.bindTooltip(
                `<div>
                     The Royal Ontario Museum (Bloor St Entrance)<br>Capacity Change: 11.0%<br> Capacity: 19<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_db255b5d90d743cebb53c9142884ea6d = L.circle(
                [43.651885, -79.3649],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_db255b5d90d743cebb53c9142884ea6d.bindTooltip(
                `<div>
                     King St E / Ontario St.<br>Capacity Change: 11.0%<br> Capacity: 14<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_084f007a316749c08f65a487945474c9 = L.circle(
                [43.6476616, -79.37549],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_084f007a316749c08f65a487945474c9.bindTooltip(
                `<div>
                     Front St E / Scott St<br>Capacity Change: 11.0%<br> Capacity: 11<br>Net Bikes: 1.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_bef916612ce141419905e3c562c1d3e3 = L.circle(
                [43.655431, -79.380653],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_bef916612ce141419905e3c562c1d3e3.bindTooltip(
                `<div>
                     Toronto Eaton Centre (Yonge St)<br>Capacity Change: 11.0%<br> Capacity: 14<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e6a7ba194b4c4b779d44862599d89a89 = L.circle(
                [43.671389, -79.382919],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e6a7ba194b4c4b779d44862599d89a89.bindTooltip(
                `<div>
                     Church St / Bloor St E<br>Capacity Change: 12.0%<br> Capacity: 15<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_078dd3809c8f442db7a6ad1b200c8a04 = L.circle(
                [43.658295, -79.372346],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_078dd3809c8f442db7a6ad1b200c8a04.bindTooltip(
                `<div>
                     Dundas St E / Pembroke St - SMART<br>Capacity Change: 12.0%<br> Capacity: 16<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_bc4946863fb848a59744d3c196550303 = L.circle(
                [43.66986, -79.398443],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_bc4946863fb848a59744d3c196550303.bindTooltip(
                `<div>
                     Taddle Creek Park<br>Capacity Change: 12.0%<br> Capacity: 15<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_18e6ba75f70444928da93e808c6f5c48 = L.circle(
                [43.6743985, -79.3986601],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_18e6ba75f70444928da93e808c6f5c48.bindTooltip(
                `<div>
                     Davenport Rd / Bedford Rd<br>Capacity Change: 12.0%<br> Capacity: 15<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c15535b639514bb8b6d61f5001b44127 = L.circle(
                [43.654004, -79.444792],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c15535b639514bb8b6d61f5001b44127.bindTooltip(
                `<div>
                     128 Sterling Ave - SMART<br>Capacity Change: 12.0%<br> Capacity: 20<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_07d8bd8ba9d141ec909ce7b1afd26f00 = L.circle(
                [43.65906, -79.393771],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_07d8bd8ba9d141ec909ce7b1afd26f00.bindTooltip(
                `<div>
                     College St / McCaul St<br>Capacity Change: 13.0%<br> Capacity: 17<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_90a4e2362e5349668ff0cd8916b55861 = L.circle(
                [43.659195, -79.329196],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_90a4e2362e5349668ff0cd8916b55861.bindTooltip(
                `<div>
                     Lakeshore Blvd E /Leslie St<br>Capacity Change: 13.0%<br> Capacity: 19<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_86b4d6bb96824ca48f7eec10919c6f7f = L.circle(
                [43.653809, -79.3595],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_86b4d6bb96824ca48f7eec10919c6f7f.bindTooltip(
                `<div>
                     Sackville St / Eastern Ave - SMART<br>Capacity Change: 13.0%<br> Capacity: 12<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_bb5cfcde939a45d3bc4d31f27edffac0 = L.circle(
                [43.662085, -79.397735],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_bb5cfcde939a45d3bc4d31f27edffac0.bindTooltip(
                `<div>
                     Willcocks St / St. George St<br>Capacity Change: 13.0%<br> Capacity: 17<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1c23c4736a5046b082decafb18654c7c = L.circle(
                [43.665461, -79.40848],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1c23c4736a5046b082decafb18654c7c.bindTooltip(
                `<div>
                     Borden St / Bloor St W - SMART<br>Capacity Change: 13.0%<br> Capacity: 12<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_747f27adf4584bfd8693c67b45d1d1e9 = L.circle(
                [43.668456, -79.393899],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_747f27adf4584bfd8693c67b45d1d1e9.bindTooltip(
                `<div>
                     Queen's Park / Bloor St W<br>Capacity Change: 14.0%<br> Capacity: 19<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e8de7b31735f481fad0fe542839883a3 = L.circle(
                [43.646734, -79.38301],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e8de7b31735f481fad0fe542839883a3.bindTooltip(
                `<div>
                     Wellington St W / York St<br>Capacity Change: 14.0%<br> Capacity: 22<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d919caf8230a43b1b49cb44b7671fa1c = L.circle(
                [43.643253094827294, -79.41230469904167],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d919caf8230a43b1b49cb44b7671fa1c.bindTooltip(
                `<div>
                     Adelaide St W / Strachan Ave<br>Capacity Change: 14.0%<br> Capacity: 15<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_590e9e20f08047ef978ef3cee8e5b75d = L.circle(
                [43.6462176, -79.3855048],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_590e9e20f08047ef978ef3cee8e5b75d.bindTooltip(
                `<div>
                     Simcoe St / Wellington St North<br>Capacity Change: 14.0%<br> Capacity: 15<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d14d85ae55984c62b1bde39b981ad146 = L.circle(
                [43.6394444, -79.42527777777778],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d14d85ae55984c62b1bde39b981ad146.bindTooltip(
                `<div>
                     King St W / Fraser Ave<br>Capacity Change: 14.0%<br> Capacity: 15<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c0251e290bd741e8817baf85c2e88f8c = L.circle(
                [43.655766, -79.3802],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c0251e290bd741e8817baf85c2e88f8c.bindTooltip(
                `<div>
                     Yonge St / Dundas Sq<br>Capacity Change: 14.0%<br> Capacity: 27<br>Net Bikes: 4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_360b420888ec416892ae96e00e6d5acb = L.circle(
                [43.660382, -79.3954],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_360b420888ec416892ae96e00e6d5acb.bindTooltip(
                `<div>
                     Gailbraith Rd / King’s College Cr. (U of T)<br>Capacity Change: 15.0%<br> Capacity: 17<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_64872d0f4b2e4bb6b186c565f60de153 = L.circle(
                [43.650077, -79.391291],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_64872d0f4b2e4bb6b186c565f60de153.bindTooltip(
                `<div>
                     Queen St W / John St<br>Capacity Change: 15.0%<br> Capacity: 23<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c25fd475ae77474692329a22def317d3 = L.circle(
                [43.641675, -79.354006],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c25fd475ae77474692329a22def317d3.bindTooltip(
                `<div>
                     Polson Pier<br>Capacity Change: 15.0%<br> Capacity: 23<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_92f7f0f5dccd4b3a8ac00b65df41ae1b = L.circle(
                [43.6521, -79.4486],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_92f7f0f5dccd4b3a8ac00b65df41ae1b.bindTooltip(
                `<div>
                     Howard Park Ave / Dundas St W - SMART<br>Capacity Change: 16.0%<br> Capacity: 12<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6b3a156ad25444218938dfdcc2ffac44 = L.circle(
                [43.669863, -79.297786],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6b3a156ad25444218938dfdcc2ffac44.bindTooltip(
                `<div>
                     Lee Ave / Queen St E<br>Capacity Change: 17.0%<br> Capacity: 11<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_4999d5de9f1342e6a0dac9f2198a33da = L.circle(
                [43.674991, -79.396273],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_4999d5de9f1342e6a0dac9f2198a33da.bindTooltip(
                `<div>
                     Davenport Rd / Avenue Rd<br>Capacity Change: 17.0%<br> Capacity: 11<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_0a05c8420cee40be84211e0b645b1f02 = L.circle(
                [43.669244, -79.3894],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_0a05c8420cee40be84211e0b645b1f02.bindTooltip(
                `<div>
                     Bay St / Bloor St W (West Side)<br>Capacity Change: 17.0%<br> Capacity: 15<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_4eb48313793f4eba87219515547c203b = L.circle(
                [43.65389, -79.4675],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_4eb48313793f4eba87219515547c203b.bindTooltip(
                `<div>
                     High Park Subway - SMART<br>Capacity Change: 18.0%<br> Capacity: 15<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_5965a43e115744988ab6b7557d3cd545 = L.circle(
                [43.6495789, -79.3762096],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_5965a43e115744988ab6b7557d3cd545.bindTooltip(
                `<div>
                     King St E / Victoria St<br>Capacity Change: 18.0%<br> Capacity: 19<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_5318648ba45e4206a53f45737da8a645 = L.circle(
                [43.650279, -79.356832],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_5318648ba45e4206a53f45737da8a645.bindTooltip(
                `<div>
                     Cherry St / Distillery Ln<br>Capacity Change: 18.0%<br> Capacity: 15<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_220528903b17456185191c8cfb94f721 = L.circle(
                [43.6591666666667, -79.3855555555556],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 19.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_220528903b17456185191c8cfb94f721.bindTooltip(
                `<div>
                     Hayter St / Laplante Ave<br>Capacity Change: 19.0%<br> Capacity: 22<br>Net Bikes: 4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_f0ff3273a7c44990be98752ba86c5029 = L.circle(
                [43.6545174, -79.3895315],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 19.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_f0ff3273a7c44990be98752ba86c5029.bindTooltip(
                `<div>
                     Dundas St W / St. Patrick St<br>Capacity Change: 19.0%<br> Capacity: 19<br>Net Bikes: 4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_78432b5603784af9a1856f411eded02b = L.circle(
                [43.680223, -79.344062],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 19.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_78432b5603784af9a1856f411eded02b.bindTooltip(
                `<div>
                     Pape Subway Green P<br>Capacity Change: 19.0%<br> Capacity: 15<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_346c1d41e4a1487a9ef3e537a7a8887b = L.circle(
                [43.643834, -79.396649],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 20.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_346c1d41e4a1487a9ef3e537a7a8887b.bindTooltip(
                `<div>
                     424 Wellington St W - SMART<br>Capacity Change: 20.0%<br> Capacity: 15<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ee28f0a1334a405989c2c5b5fc91276f = L.circle(
                [43.6704537, -79.39014],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 20.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ee28f0a1334a405989c2c5b5fc91276f.bindTooltip(
                `<div>
                     Cumberland Ave / Bay St SMART<br>Capacity Change: 20.0%<br> Capacity: 12<br>Net Bikes: 2.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_eff4c33ba36d41b0a92c52743a3b1e6a = L.circle(
                [43.6508333333333, -79.4430555555556],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 20.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_eff4c33ba36d41b0a92c52743a3b1e6a.bindTooltip(
                `<div>
                     Sterling Rd / Dundas St W<br>Capacity Change: 20.0%<br> Capacity: 19<br>Net Bikes: 4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_b8e4f08383b14de2b7b0674c8b45780c = L.circle(
                [43.643975, -79.419576],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_b8e4f08383b14de2b7b0674c8b45780c.bindTooltip(
                `<div>
                     Queen St W / Ossington Ave<br>Capacity Change: 21.0%<br> Capacity: 23<br>Net Bikes: 5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6b051117a94440849ec2bbb4be24bbc3 = L.circle(
                [43.652777, -79.372637],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6b051117a94440849ec2bbb4be24bbc3.bindTooltip(
                `<div>
                     Jarvis St / Richmond St E<br>Capacity Change: 21.0%<br> Capacity: 19<br>Net Bikes: 4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_8ff93fd7fb94464a87cbc6bc0f5d2606 = L.circle(
                [43.669604, -79.381171],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_8ff93fd7fb94464a87cbc6bc0f5d2606.bindTooltip(
                `<div>
                     Charles St E / Jarvis St - SMART<br>Capacity Change: 21.0%<br> Capacity: 19<br>Net Bikes: 4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d657f5eafb06424c9990c03ac0df25aa = L.circle(
                [43.656094, -79.381484],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 22.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d657f5eafb06424c9990c03ac0df25aa.bindTooltip(
                `<div>
                     Dundas St W / Yonge St<br>Capacity Change: 22.0%<br> Capacity: 15<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c53c141d53924a9a867ab6298ba176ce = L.circle(
                [43.641389, -79.404444],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 22.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c53c141d53924a9a867ab6298ba176ce.bindTooltip(
                `<div>
                     Niagara St / Tecumseth St<br>Capacity Change: 22.0%<br> Capacity: 15<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_d6f4b990acea447d8e545b0ed763862d = L.circle(
                [43.6451635, -79.3831757],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 25.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_d6f4b990acea447d8e545b0ed763862d.bindTooltip(
                `<div>
                     Front St W / University Ave (1)<br>Capacity Change: 25.0%<br> Capacity: 19<br>Net Bikes: 5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_8e208b1654bd4ed287923aaaeb4718d6 = L.circle(
                [43.649722, -79.416944],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_8e208b1654bd4ed287923aaaeb4718d6.bindTooltip(
                `<div>
                     Dundas St W / Crawford St<br>Capacity Change: 26.0%<br> Capacity: 19<br>Net Bikes: 5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_bd461fa9b372415790c9fd031d83f8a0 = L.circle(
                [43.643667, -79.380414],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 27.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_bd461fa9b372415790c9fd031d83f8a0.bindTooltip(
                `<div>
                     25 York St – Union Station South<br>Capacity Change: 27.0%<br> Capacity: 11<br>Net Bikes: 3.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_028d82bcad034d14b52d1ebb8f135806 = L.circle(
                [43.650745, -79.383633],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_028d82bcad034d14b52d1ebb8f135806.bindTooltip(
                `<div>
                     Richmond St W / York St<br>Capacity Change: 28.0%<br> Capacity: 17<br>Net Bikes: 5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_128cb675e67c4f31a781d3a5e9bdc61a = L.circle(
                [43.6448257, -79.3993258],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_128cb675e67c4f31a781d3a5e9bdc61a.bindTooltip(
                `<div>
                     King St W / Portland St<br>Capacity Change: 28.0%<br> Capacity: 19<br>Net Bikes: 5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a3bf6519d44a466aa12700ae25922f0c = L.circle(
                [43.6783213, -79.35822],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 29.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a3bf6519d44a466aa12700ae25922f0c.bindTooltip(
                `<div>
                     Pretoria Av / Broadview Av<br>Capacity Change: 29.0%<br> Capacity: 19<br>Net Bikes: 5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_38191f50342944f881e2618ad52ee52e = L.circle(
                [43.64422, -79.36927],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 31.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_38191f50342944f881e2618ad52ee52e.bindTooltip(
                `<div>
                     Lower Jarvis / Queens Quay E<br>Capacity Change: 31.0%<br> Capacity: 19<br>Net Bikes: 6.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ff44891d70f6484f8ed3a76544616761 = L.circle(
                [43.6507021, -79.3800546],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 32.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ff44891d70f6484f8ed3a76544616761.bindTooltip(
                `<div>
                     Temperance St. Station<br>Capacity Change: 32.0%<br> Capacity: 19<br>Net Bikes: 6.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_dd6b2c17d8a0481eb131000079ce488e = L.circle(
                [43.652276, -79.380701],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 33.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_dd6b2c17d8a0481eb131000079ce488e.bindTooltip(
                `<div>
                     Queen St W / James St<br>Capacity Change: 33.0%<br> Capacity: 11<br>Net Bikes: 4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_4bd5a5bccde647f1aeffcc2f69753540 = L.circle(
                [43.656026, -79.385327],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 34.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_4bd5a5bccde647f1aeffcc2f69753540.bindTooltip(
                `<div>
                     Elizabeth St / Edward St (Bus Terminal)<br>Capacity Change: 34.0%<br> Capacity: 15<br>Net Bikes: 5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_416d0d8d87d44ddba93f46cff1d31770 = L.circle(
                [43.661803, -79.389682],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 35.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_416d0d8d87d44ddba93f46cff1d31770.bindTooltip(
                `<div>
                     Queen's Park Cres E / Grosvenor St - SMART<br>Capacity Change: 35.0%<br> Capacity: 12<br>Net Bikes: 4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ddcf1a588b6b4271a65d9ba800e43889 = L.circle(
                [43.646162, -79.378912],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 37.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ddcf1a588b6b4271a65d9ba800e43889.bindTooltip(
                `<div>
                     Front St W / Bay St (North Side)<br>Capacity Change: 37.0%<br> Capacity: 11<br>Net Bikes: 4.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_6ad31a6dd8134eed8acb8ee18b26349e = L.circle(
                [43.648, -79.3834],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_6ad31a6dd8134eed8acb8ee18b26349e.bindTooltip(
                `<div>
                     York St / King St W - SMART<br>Capacity Change: 38.0%<br> Capacity: 16<br>Net Bikes: 6.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1fce5758ed1448a498e868e11487808c = L.circle(
                [43.6856, -79.3718],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1fce5758ed1448a498e868e11487808c.bindTooltip(
                `<div>
                     Chorley Park - SMART<br>Capacity Change: 38.0%<br> Capacity: 20<br>Net Bikes: 8.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_c925c4c89c1c47c580e427d9114bbb4a = L.circle(
                [43.6525077, -79.4654233],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 38.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_c925c4c89c1c47c580e427d9114bbb4a.bindTooltip(
                `<div>
                     High Park - West Rd<br>Capacity Change: 38.0%<br> Capacity: 23<br>Net Bikes: 9.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_ba4d0e0bfa8c4b3e9ec31f4fdacb176c = L.circle(
                [43.651838, -79.378743],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 41.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_ba4d0e0bfa8c4b3e9ec31f4fdacb176c.bindTooltip(
                `<div>
                     Richmond St E / Yonge St<br>Capacity Change: 41.0%<br> Capacity: 17<br>Net Bikes: 7.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_cc99c8cdbcf342bab1796787a36f3b92 = L.circle(
                [43.6580442, -79.3927404],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 44.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_cc99c8cdbcf342bab1796787a36f3b92.bindTooltip(
                `<div>
                     Orde St / McCaul St - SMART<br>Capacity Change: 44.0%<br> Capacity: 15<br>Net Bikes: 7.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_65fd4bd9b8e440179449de057d6ee023 = L.circle(
                [43.647259, -79.379878],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 44.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_65fd4bd9b8e440179449de057d6ee023.bindTooltip(
                `<div>
                     Wellington St W / Bay St<br>Capacity Change: 44.0%<br> Capacity: 27<br>Net Bikes: 12.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_341d04ed5a664094a58875131a90fad9 = L.circle(
                [43.653236, -79.376716],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 45.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_341d04ed5a664094a58875131a90fad9.bindTooltip(
                `<div>
                     Bond St / Queen St E<br>Capacity Change: 45.0%<br> Capacity: 25<br>Net Bikes: 11.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a5100ac78baf4fcd99d7e407bfc85667 = L.circle(
                [43.6575, -79.39527777777778],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 45.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a5100ac78baf4fcd99d7e407bfc85667.bindTooltip(
                `<div>
                     Beverley St / College St<br>Capacity Change: 45.0%<br> Capacity: 23<br>Net Bikes: 10.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_80638f75f6af4896af9c43ab10caceb5 = L.circle(
                [43.6523, -79.4058],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 45.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_80638f75f6af4896af9c43ab10caceb5.bindTooltip(
                `<div>
                     Bathurst St / Dundas St W<br>Capacity Change: 45.0%<br> Capacity: 41<br>Net Bikes: 19.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_840c532d23d54f8c9d1cafe985211b04 = L.circle(
                [43.648928, -79.378623],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 45.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_840c532d23d54f8c9d1cafe985211b04.bindTooltip(
                `<div>
                     King St W / Jordan St<br>Capacity Change: 45.0%<br> Capacity: 11<br>Net Bikes: 5.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_43cd4c5b13eb4cc39fb473df2ef00640 = L.circle(
                [43.650152, -79.379856],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 49.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_43cd4c5b13eb4cc39fb473df2ef00640.bindTooltip(
                `<div>
                     Adelaide St W / Bay St - SMART<br>Capacity Change: 49.0%<br> Capacity: 20<br>Net Bikes: 10.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_a1d5dea8347b4024899e8d5e2b564a94 = L.circle(
                [43.6848652, -79.356602],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 50.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_a1d5dea8347b4024899e8d5e2b564a94.bindTooltip(
                `<div>
                     Broadview Ave / Westwood Ave<br>Capacity Change: 50.0%<br> Capacity: 23<br>Net Bikes: 12.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_05344c1cb7dd4360baf223ed341e2707 = L.circle(
                [43.683296, -79.418734],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 55.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_05344c1cb7dd4360baf223ed341e2707.bindTooltip(
                `<div>
                     St Clair Ave W / Bathurst St.<br>Capacity Change: 55.0%<br> Capacity: 19<br>Net Bikes: 10.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_5acf393953394cdcb962e9d39e3d3d9b = L.circle(
                [43.667333, -79.399429],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 55.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_5acf393953394cdcb962e9d39e3d3d9b.bindTooltip(
                `<div>
                     St. George St / Bloor St W<br>Capacity Change: 55.0%<br> Capacity: 19<br>Net Bikes: 10.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_b89e3cfde17c4f368d85a09fa4a4a5a9 = L.circle(
                [43.678401, -79.346289],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 56.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_b89e3cfde17c4f368d85a09fa4a4a5a9.bindTooltip(
                `<div>
                     Danforth Ave / Gough Ave<br>Capacity Change: 56.0%<br> Capacity: 17<br>Net Bikes: 10.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_eb09a2fef08348738039d8eedf54044e = L.circle(
                [43.656518, -79.389099],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 62.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_eb09a2fef08348738039d8eedf54044e.bindTooltip(
                `<div>
                     University Ave / Elm St<br>Capacity Change: 62.0%<br> Capacity: 11<br>Net Bikes: 7.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_71a2e9c49b444fcd9dae039d2fae39c1 = L.circle(
                [43.659226, -79.390213],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 68.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_71a2e9c49b444fcd9dae039d2fae39c1.bindTooltip(
                `<div>
                     University Ave / College St (West)<br>Capacity Change: 68.0%<br> Capacity: 11<br>Net Bikes: 8.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_8d9de63bfd084c1d89aec4eaf75d276e = L.circle(
                [43.665527, -79.387499],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 70.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_8d9de63bfd084c1d89aec4eaf75d276e.bindTooltip(
                `<div>
                     Bay St / St. Joseph St<br>Capacity Change: 70.0%<br> Capacity: 15<br>Net Bikes: 10.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_1b85b0f654514c84be026d9b604f739f = L.circle(
                [43.657763, -79.389165],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 73.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_1b85b0f654514c84be026d9b604f739f.bindTooltip(
                `<div>
                     University Ave / Gerrard St W<br>Capacity Change: 73.0%<br> Capacity: 25<br>Net Bikes: 18.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_e788d0c980bd464b9ab5b7d52296ea66 = L.circle(
                [43.64852, -79.380576],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 75.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_e788d0c980bd464b9ab5b7d52296ea66.bindTooltip(
                `<div>
                     King St W / Bay St (West Side)<br>Capacity Change: 75.0%<br> Capacity: 19<br>Net Bikes: 14.0
                 </div>`,
                {"sticky": true}
            );
        
    
            var circle_7a65b27396314d1eb7ec1e841d30485f = L.circle(
                [43.65995, -79.38964],
                {"bubblingMouseEvents": true, "color": "#008000", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "#008000", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 90.0, "stroke": true, "weight": 3}
            ).addTo(map_ec2093b164e840cc90050ded3bb6d819);
        
    
            circle_7a65b27396314d1eb7ec1e841d30485f.bindTooltip(
                `<div>
                     University Ave / College St (East)<br>Capacity Change: 90.0%<br> Capacity: 14<br>Net Bikes: 13.0
                 </div>`,
                {"sticky": true}
            );
        
</script>
            </div>
        </div>
    </div>
</pre>
```

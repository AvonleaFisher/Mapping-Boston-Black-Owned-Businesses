## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown
<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.4.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.4.0/dist/leaflet.css"/>
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
                #map_573f4e54306a4a1ca900cc7b86a142f5 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_573f4e54306a4a1ca900cc7b86a142f5" ></div>
        
</body>
<script>    
    
            var map_573f4e54306a4a1ca900cc7b86a142f5 = L.map(
                "map_573f4e54306a4a1ca900cc7b86a142f5",
                {
                    center: [42.361145, -71.057083],
                    crs: L.CRS.EPSG3857,
                    zoom: 12,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_a22febe77b8a4c789e4280453c6a28ed = L.tileLayer(
                "https://stamen-tiles-{s}.a.ssl.fastly.net/toner/{z}/{x}/{y}.png",
                {"attribution": "Map tiles by \u003ca href=\"http://stamen.com\"\u003eStamen Design\u003c/a\u003e, under \u003ca href=\"http://creativecommons.org/licenses/by/3.0\"\u003eCC BY 3.0\u003c/a\u003e. Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var marker_6a0880bb42804c9f964c095fdee2a826 = L.marker(
                [42.35234324579048, -71.14057657362147],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_69cea38dd9124e18a63766869a11da88 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_6a0880bb42804c9f964c095fdee2a826.setIcon(icon_69cea38dd9124e18a63766869a11da88);
        
    
        var popup_7846421b8c4d47a0b7f75653595ef0e4 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_8e983544a5d54b6a9d376454880475a4 = $(`<div id="html_8e983544a5d54b6a9d376454880475a4" style="width: 100.0%; height: 100.0%;">Rock City Pizza, 568 Cambridge St, Allston, MA 02134</div>`)[0];
            popup_7846421b8c4d47a0b7f75653595ef0e4.setContent(html_8e983544a5d54b6a9d376454880475a4);
        

        marker_6a0880bb42804c9f964c095fdee2a826.bindPopup(popup_7846421b8c4d47a0b7f75653595ef0e4)
        ;

        
    
    
            var marker_9d21b24b93fb4b2694f316c287205074 = L.marker(
                [42.1233109, -71.04093977352116],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_461869c4c7cd4a7bbf5c75a2d2c8cb3c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_9d21b24b93fb4b2694f316c287205074.setIcon(icon_461869c4c7cd4a7bbf5c75a2d2c8cb3c);
        
    
        var popup_1a767f80368e42349b4d6537341e32a1 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_088f64c637374c49a288b109594c61a1 = $(`<div id="html_088f64c637374c49a288b109594c61a1" style="width: 100.0%; height: 100.0%;">TamBos Kitchen, 490 W Main St, Avon, MA 02322</div>`)[0];
            popup_1a767f80368e42349b4d6537341e32a1.setContent(html_088f64c637374c49a288b109594c61a1);
        

        marker_9d21b24b93fb4b2694f316c287205074.bindPopup(popup_1a767f80368e42349b4d6537341e32a1)
        ;

        
    
    
            var marker_856c5d771861406aaab4b451cba1c8ff = L.marker(
                [42.306916, -71.06641185714285],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_6f078f9fbcce4a4381c7f30e3fc9e97d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_856c5d771861406aaab4b451cba1c8ff.setIcon(icon_6f078f9fbcce4a4381c7f30e3fc9e97d);
        
    
        var popup_2f7cf797b25342dbad76e147614d4896 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_7cdce96f3fa648bc84dd227ce45dd6c7 = $(`<div id="html_7cdce96f3fa648bc84dd227ce45dd6c7" style="width: 100.0%; height: 100.0%;">Restaurante Cesaria, 266 Bowdoin St, Boston, MA 02122</div>`)[0];
            popup_2f7cf797b25342dbad76e147614d4896.setContent(html_7cdce96f3fa648bc84dd227ce45dd6c7);
        

        marker_856c5d771861406aaab4b451cba1c8ff.bindPopup(popup_2f7cf797b25342dbad76e147614d4896)
        ;

        
    
    
            var marker_91fe8d2b42634ad299039dc40ce8b644 = L.marker(
                [42.27349409420357, -71.06784218408322],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_09508b105e3c4c55af6eb8ad2b3568fd = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_91fe8d2b42634ad299039dc40ce8b644.setIcon(icon_09508b105e3c4c55af6eb8ad2b3568fd);
        
    
        var popup_af9ed186feb449ffb40c1b71b66c209a = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_46e75c6acd1244c6bd76fd4c8aefb0e9 = $(`<div id="html_46e75c6acd1244c6bd76fd4c8aefb0e9" style="width: 100.0%; height: 100.0%;">Bred Gourmet, 2255 Dorchester Ave, Boston, MA 02124</div>`)[0];
            popup_af9ed186feb449ffb40c1b71b66c209a.setContent(html_46e75c6acd1244c6bd76fd4c8aefb0e9);
        

        marker_91fe8d2b42634ad299039dc40ce8b644.bindPopup(popup_af9ed186feb449ffb40c1b71b66c209a)
        ;

        
    
    
            var marker_0caff3fa5a034c7faa0fc46ae06fe2a7 = L.marker(
                [42.3398422, -71.0824905],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_e30964d4e7764ce1a2624c8d0bc879fa = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_0caff3fa5a034c7faa0fc46ae06fe2a7.setIcon(icon_e30964d4e7764ce1a2624c8d0bc879fa);
        
    
        var popup_476ff980c45644e1ab0b0afdb4e38af6 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_e173764e3eeb48d5b04e21c6ca436799 = $(`<div id="html_e173764e3eeb48d5b04e21c6ca436799" style="width: 100.0%; height: 100.0%;">Darryl&#39;s Corner Bar and Kitchen, 604 Columbus Ave, Boston, MA 02118</div>`)[0];
            popup_476ff980c45644e1ab0b0afdb4e38af6.setContent(html_e173764e3eeb48d5b04e21c6ca436799);
        

        marker_0caff3fa5a034c7faa0fc46ae06fe2a7.bindPopup(popup_476ff980c45644e1ab0b0afdb4e38af6)
        ;

        
    
    
            var marker_d2e626d196dc45a0ac5f5f9598d977b9 = L.marker(
                [42.31909466396804, -71.08173560939963],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_0807c22bac504c18b64f1f3f35d28b13 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_d2e626d196dc45a0ac5f5f9598d977b9.setIcon(icon_0807c22bac504c18b64f1f3f35d28b13);
        
    
        var popup_af9e022fba00404eb26a93a29784f773 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_15b56df045eb46e6a235d5562b88e227 = $(`<div id="html_15b56df045eb46e6a235d5562b88e227" style="width: 100.0%; height: 100.0%;">District 7 Tavern, 380 Warren St, Roxbury, MA 02119</div>`)[0];
            popup_af9e022fba00404eb26a93a29784f773.setContent(html_15b56df045eb46e6a235d5562b88e227);
        

        marker_d2e626d196dc45a0ac5f5f9598d977b9.bindPopup(popup_af9e022fba00404eb26a93a29784f773)
        ;

        
    
    
            var marker_6ebed277d3e6462287c55da4c456fe33 = L.marker(
                [42.31040284013719, -71.0833121378241],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_b0d362db822d42a3bd35f0c3525f5238 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_6ebed277d3e6462287c55da4c456fe33.setIcon(icon_b0d362db822d42a3bd35f0c3525f5238);
        
    
        var popup_c6403553dd1446dfbf484a70d1573a71 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_0cdcec8926d846c29da57b982f4b03b5 = $(`<div id="html_0cdcec8926d846c29da57b982f4b03b5" style="width: 100.0%; height: 100.0%;">Food for the Soul, 651 Warren St, Boston, MA 02121</div>`)[0];
            popup_c6403553dd1446dfbf484a70d1573a71.setContent(html_0cdcec8926d846c29da57b982f4b03b5);
        

        marker_6ebed277d3e6462287c55da4c456fe33.bindPopup(popup_c6403553dd1446dfbf484a70d1573a71)
        ;

        
    
    
            var marker_08f7674535854cd38eaf7b94bb700faa = L.marker(
                [42.337577887995266, -71.08337615618235],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_ee21475520f1414a87f1f59b4c92005d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_08f7674535854cd38eaf7b94bb700faa.setIcon(icon_ee21475520f1414a87f1f59b4c92005d);
        
    
        var popup_7cb16b82d9e34b4492f155d1412fe970 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_74d1a612c1ca4fb9a813959ca4f63d6d = $(`<div id="html_74d1a612c1ca4fb9a813959ca4f63d6d" style="width: 100.0%; height: 100.0%;">Slades Bar and Grill, 958 Tremont St, Boston, MA 02120</div>`)[0];
            popup_7cb16b82d9e34b4492f155d1412fe970.setContent(html_74d1a612c1ca4fb9a813959ca4f63d6d);
        

        marker_08f7674535854cd38eaf7b94bb700faa.bindPopup(popup_7cb16b82d9e34b4492f155d1412fe970)
        ;

        
    
    
            var marker_57ecc616e7a0406d92d25910e19ae361 = L.marker(
                [42.340631450000004, -71.08222834999998],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_3a12d0cc747f4ae9b0afa2a8c9ea4143 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_57ecc616e7a0406d92d25910e19ae361.setIcon(icon_3a12d0cc747f4ae9b0afa2a8c9ea4143);
        
    
        var popup_ecf0d928681345a6856283d034205d78 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_c3d4502873fd492480f98b66fa7fe589 = $(`<div id="html_c3d4502873fd492480f98b66fa7fe589" style="width: 100.0%; height: 100.0%;">Wally&#39;s Café, 427 Massachusetts Ave, Boston, MA 02118</div>`)[0];
            popup_ecf0d928681345a6856283d034205d78.setContent(html_c3d4502873fd492480f98b66fa7fe589);
        

        marker_57ecc616e7a0406d92d25910e19ae361.bindPopup(popup_ecf0d928681345a6856283d034205d78)
        ;

        
    
    
            var marker_e3b704f691da42f6b330924912bb03bd = L.marker(
                [42.327935502100544, -71.07757817254648],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_daaa08d25f1f41088735cf2fb39ee9d7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_e3b704f691da42f6b330924912bb03bd.setIcon(icon_daaa08d25f1f41088735cf2fb39ee9d7);
        
    
        var popup_a3c523e1438d492f990c7e5cc72b30db = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_65f887a963754f8fa08f1ba02be3b94b = $(`<div id="html_65f887a963754f8fa08f1ba02be3b94b" style="width: 100.0%; height: 100.0%;">Maxine&#39;s on Saint James, 304 Dudley St, Boston, MA 02119</div>`)[0];
            popup_a3c523e1438d492f990c7e5cc72b30db.setContent(html_65f887a963754f8fa08f1ba02be3b94b);
        

        marker_e3b704f691da42f6b330924912bb03bd.bindPopup(popup_a3c523e1438d492f990c7e5cc72b30db)
        ;

        
    
    
            var marker_be031124ca6b46fc9f830dbfbbb53499 = L.marker(
                [42.32423004001341, -71.06822158813175],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_2c5484f20d164c9abb0a279e252ac3a8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_be031124ca6b46fc9f830dbfbbb53499.setIcon(icon_2c5484f20d164c9abb0a279e252ac3a8);
        
    
        var popup_c5ca8a2a3825400ca561540d66511697 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_b8f1cc010cff464187c8e2dfb3223ff9 = $(`<div id="html_b8f1cc010cff464187c8e2dfb3223ff9" style="width: 100.0%; height: 100.0%;">Top Mix Bar &amp; Kitchen, 257 Norfolk Ave, Boston, MA 02119</div>`)[0];
            popup_c5ca8a2a3825400ca561540d66511697.setContent(html_b8f1cc010cff464187c8e2dfb3223ff9);
        

        marker_be031124ca6b46fc9f830dbfbbb53499.bindPopup(popup_c5ca8a2a3825400ca561540d66511697)
        ;

        
    
    
            var marker_257b42fd7d4c46439203750eacb4eeb2 = L.marker(
                [42.312852, -71.07445],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_1f302c1defa8423cb4f3ab0af957e410 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_257b42fd7d4c46439203750eacb4eeb2.setIcon(icon_1f302c1defa8423cb4f3ab0af957e410);
        
    
        var popup_0f8a572ef7e94a1eb3e1d1683515fab8 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_5bf2b62df27e461987705eb2e07e01a4 = $(`<div id="html_5bf2b62df27e461987705eb2e07e01a4" style="width: 100.0%; height: 100.0%;">Clarke&#39;s Cakes and Cookies, 196 Quincy St, Boston, MA 02121</div>`)[0];
            popup_0f8a572ef7e94a1eb3e1d1683515fab8.setContent(html_5bf2b62df27e461987705eb2e07e01a4);
        

        marker_257b42fd7d4c46439203750eacb4eeb2.bindPopup(popup_0f8a572ef7e94a1eb3e1d1683515fab8)
        ;

        
    
    
            var marker_30c1c528dda54b60a5278bdfefcd9f71 = L.marker(
                [42.3034811, -71.0851665],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_b5d75ae3cc4842e8a72930311d823cac = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_30c1c528dda54b60a5278bdfefcd9f71.setIcon(icon_b5d75ae3cc4842e8a72930311d823cac);
        
    
        var popup_710e6bad49b0467e870bd8063afd362c = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_a8bac690aeea4c8ca179fcc216303fec = $(`<div id="html_a8bac690aeea4c8ca179fcc216303fec" style="width: 100.0%; height: 100.0%;">Family Affair Catering, 554 Columbia Rd, Dorchester, MA 02125</div>`)[0];
            popup_710e6bad49b0467e870bd8063afd362c.setContent(html_a8bac690aeea4c8ca179fcc216303fec);
        

        marker_30c1c528dda54b60a5278bdfefcd9f71.bindPopup(popup_710e6bad49b0467e870bd8063afd362c)
        ;

        
    
    
            var marker_43124f7a16a24ed58d6a2ab37a4a07c5 = L.marker(
                [42.30891932312241, -71.08269989633494],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_2dd23e40d544460d8e722215272650fc = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_43124f7a16a24ed58d6a2ab37a4a07c5.setIcon(icon_2dd23e40d544460d8e722215272650fc);
        
    
        var popup_639f48c93f5a46189ed3ecfe63710044 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_53c82427d8fb4f109f8fe2bc1314e59b = $(`<div id="html_53c82427d8fb4f109f8fe2bc1314e59b" style="width: 100.0%; height: 100.0%;">Flames Restaurant, 469 Blue Hill Ave, Boston, MA 02121</div>`)[0];
            popup_639f48c93f5a46189ed3ecfe63710044.setContent(html_53c82427d8fb4f109f8fe2bc1314e59b);
        

        marker_43124f7a16a24ed58d6a2ab37a4a07c5.bindPopup(popup_639f48c93f5a46189ed3ecfe63710044)
        ;

        
    
    
            var marker_b9a58eb65fa446d6b356fbc4f1159f50 = L.marker(
                [42.3415773, -71.0864927],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_205a93ffdbb841e6a5637a2a30c41dfe = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_b9a58eb65fa446d6b356fbc4f1159f50.setIcon(icon_205a93ffdbb841e6a5637a2a30c41dfe);
        
    
        var popup_63fa12a097b94dc690a7ee5ee02cd53d = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_587fdb09b299461aa1ac66aa3fa1b58c = $(`<div id="html_587fdb09b299461aa1ac66aa3fa1b58c" style="width: 100.0%; height: 100.0%;">Flames Restaurant II, 746 Huntington Ave, Boston, MA 02115</div>`)[0];
            popup_63fa12a097b94dc690a7ee5ee02cd53d.setContent(html_587fdb09b299461aa1ac66aa3fa1b58c);
        

        marker_b9a58eb65fa446d6b356fbc4f1159f50.bindPopup(popup_63fa12a097b94dc690a7ee5ee02cd53d)
        ;

        
    
    
            var marker_0ae97b856c9c409d8b81bc53f4b2a681 = L.marker(
                [42.312852, -71.07445],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_42901e217e874fc484d4ca9709f8f10f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_0ae97b856c9c409d8b81bc53f4b2a681.setIcon(icon_42901e217e874fc484d4ca9709f8f10f);
        
    
        var popup_eaed6e83b70d41e2b4086cc8a1943153 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_b9deef527e0b4b44bb8daa6e0c3cfbea = $(`<div id="html_b9deef527e0b4b44bb8daa6e0c3cfbea" style="width: 100.0%; height: 100.0%;">Fresh Food Generation, 196 Quincy St, Boston, MA 02125</div>`)[0];
            popup_eaed6e83b70d41e2b4086cc8a1943153.setContent(html_b9deef527e0b4b44bb8daa6e0c3cfbea);
        

        marker_0ae97b856c9c409d8b81bc53f4b2a681.bindPopup(popup_eaed6e83b70d41e2b4086cc8a1943153)
        ;

        
    
    
            var marker_1b75a70a263d4a7184ed7e1fe0949455 = L.marker(
                [42.29964066186969, -71.07378912722358],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_00f3320e5c03425386f1f6edb71507c7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_1b75a70a263d4a7184ed7e1fe0949455.setIcon(icon_00f3320e5c03425386f1f6edb71507c7);
        
    
        var popup_54553e116cba4d0f917cecd257edfdfd = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_e04b0fb19260432daaf3aee54c5ecd2b = $(`<div id="html_e04b0fb19260432daaf3aee54c5ecd2b" style="width: 100.0%; height: 100.0%;">Oasis Vegan Veggie Parlor, 340 Washington St, Boston, MA 02121</div>`)[0];
            popup_54553e116cba4d0f917cecd257edfdfd.setContent(html_e04b0fb19260432daaf3aee54c5ecd2b);
        

        marker_1b75a70a263d4a7184ed7e1fe0949455.bindPopup(popup_54553e116cba4d0f917cecd257edfdfd)
        ;

        
    
    
            var marker_ca79ebca2c7648d2bd6265a8e28e36f2 = L.marker(
                [42.35034761690001, -71.05865541074418],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_76d4712ed67e438caff643e56fa24fcc = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_ca79ebca2c7648d2bd6265a8e28e36f2.setIcon(icon_76d4712ed67e438caff643e56fa24fcc);
        
    
        var popup_271a66f36bef4bfa921c529d50d412a4 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_7a7307a7800d43d1847cab0005e2bc95 = $(`<div id="html_7a7307a7800d43d1847cab0005e2bc95" style="width: 100.0%; height: 100.0%;">Savvor Restaurant and Lounge, 180 Lincoln St, Boston, MA 02111</div>`)[0];
            popup_271a66f36bef4bfa921c529d50d412a4.setContent(html_7a7307a7800d43d1847cab0005e2bc95);
        

        marker_ca79ebca2c7648d2bd6265a8e28e36f2.bindPopup(popup_271a66f36bef4bfa921c529d50d412a4)
        ;

        
    
    
            var marker_9eb691005b94454e83e3bca6366f5438 = L.marker(
                [42.255895853213275, -71.12265904761315],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_99ddda33241242c4a8d4f21c8972c6ae = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_9eb691005b94454e83e3bca6366f5438.setIcon(icon_99ddda33241242c4a8d4f21c8972c6ae);
        
    
        var popup_60f143b24d5747318c8105773386bd46 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_b5915955801845a28a5dca5ec747c74c = $(`<div id="html_b5915955801845a28a5dca5ec747c74c" style="width: 100.0%; height: 100.0%;">Zaz Restaurant, 1238 River St, Boston, MA 02136</div>`)[0];
            popup_60f143b24d5747318c8105773386bd46.setContent(html_b5915955801845a28a5dca5ec747c74c);
        

        marker_9eb691005b94454e83e3bca6366f5438.bindPopup(popup_60f143b24d5747318c8105773386bd46)
        ;

        
    
    
            var marker_7159418ff4214f108397c3ef9a1bbdcc = L.marker(
                [42.3390224, -71.0804718],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_c04b24c845b54f14a06122fb0f9c38c8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_7159418ff4214f108397c3ef9a1bbdcc.setIcon(icon_c04b24c845b54f14a06122fb0f9c38c8);
        
    
        var popup_cf6a6a7add1945ceb0f89904f1ff0cf3 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_9ff265afa06a42d19bdef073d0ccf076 = $(`<div id="html_9ff265afa06a42d19bdef073d0ccf076" style="width: 100.0%; height: 100.0%;">MIDA Restaurant, 782 Tremont St, Boston, MA 02118</div>`)[0];
            popup_cf6a6a7add1945ceb0f89904f1ff0cf3.setContent(html_9ff265afa06a42d19bdef073d0ccf076);
        

        marker_7159418ff4214f108397c3ef9a1bbdcc.bindPopup(popup_cf6a6a7add1945ceb0f89904f1ff0cf3)
        ;

        
    
    
            var marker_182b4fe1c4324ab18d1025909db8b63f = L.marker(
                [42.3286333, -71.0837823],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_1ff9f99fefe3453ea2a12f03117fb205 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_182b4fe1c4324ab18d1025909db8b63f.setIcon(icon_1ff9f99fefe3453ea2a12f03117fb205);
        
    
        var popup_e2de52d4ce5148609b92c4e6d62f5d19 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_b649e479f39142d6bc3ea4f86711f1bd = $(`<div id="html_b649e479f39142d6bc3ea4f86711f1bd" style="width: 100.0%; height: 100.0%;">Ideal Sub Shop, 522 Dudley St, Roxbury, MA 02119</div>`)[0];
            popup_e2de52d4ce5148609b92c4e6d62f5d19.setContent(html_b649e479f39142d6bc3ea4f86711f1bd);
        

        marker_182b4fe1c4324ab18d1025909db8b63f.bindPopup(popup_e2de52d4ce5148609b92c4e6d62f5d19)
        ;

        
    
    
            var marker_54140446ea514dfba007cd7eeb700e42 = L.marker(
                [42.29489244444444, -71.07191822222222],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_e1fb11ad40fd4b52ab6a79fa9bc6860d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_54140446ea514dfba007cd7eeb700e42.setIcon(icon_e1fb11ad40fd4b52ab6a79fa9bc6860d);
        
    
        var popup_32e6f37fdf57462bb391a5f4972e5405 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_2467af90bfef4fbeb9d9818e832db6a8 = $(`<div id="html_2467af90bfef4fbeb9d9818e832db6a8" style="width: 100.0%; height: 100.0%;">JP Roti Shop, 482 Washington St, Boston, MA 02124</div>`)[0];
            popup_32e6f37fdf57462bb391a5f4972e5405.setContent(html_2467af90bfef4fbeb9d9818e832db6a8);
        

        marker_54140446ea514dfba007cd7eeb700e42.bindPopup(popup_32e6f37fdf57462bb391a5f4972e5405)
        ;

        
    
    
            var marker_9864a3a99945412781a49da80b13a16d = L.marker(
                [42.3467199, -71.0747264],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_b13b369dd1874047a35dfe65db7e47b4 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_9864a3a99945412781a49da80b13a16d.setIcon(icon_b13b369dd1874047a35dfe65db7e47b4);
        
    
        var popup_f8f7ee3b89ab4152876c4d96ba02b8d6 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_7c35d917d49946e98ea8f148e5a750a0 = $(`<div id="html_7c35d917d49946e98ea8f148e5a750a0" style="width: 100.0%; height: 100.0%;">Urban Grape, 303 Columbus Ave, Boston, MA 02116</div>`)[0];
            popup_f8f7ee3b89ab4152876c4d96ba02b8d6.setContent(html_7c35d917d49946e98ea8f148e5a750a0);
        

        marker_9864a3a99945412781a49da80b13a16d.bindPopup(popup_f8f7ee3b89ab4152876c4d96ba02b8d6)
        ;

        
    
    
            var marker_10e7508a3f194d92842c7ba3c00d5479 = L.marker(
                [42.270496449999996, -71.09322265],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_eced7b5739f54868bfb2314119598f39 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_10e7508a3f194d92842c7ba3c00d5479.setIcon(icon_eced7b5739f54868bfb2314119598f39);
        
    
        var popup_5f883e94b81c493687a67f627faea7ba = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_ebf4b6f6c9874258bfa598b810857a3d = $(`<div id="html_ebf4b6f6c9874258bfa598b810857a3d" style="width: 100.0%; height: 100.0%;">Shea Butter Smoothies, 1556 Blue Hill Avenue, Mattapan, MA 02126</div>`)[0];
            popup_5f883e94b81c493687a67f627faea7ba.setContent(html_ebf4b6f6c9874258bfa598b810857a3d);
        

        marker_10e7508a3f194d92842c7ba3c00d5479.bindPopup(popup_5f883e94b81c493687a67f627faea7ba)
        ;

        
    
    
            var marker_8f7e15ffe4fa4177b5bc15fc40ca4fd3 = L.marker(
                [42.280965231957424, -71.08467461606152],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_d0aa9ccb53c84dc6a34b4720e0da978a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_8f7e15ffe4fa4177b5bc15fc40ca4fd3.setIcon(icon_d0aa9ccb53c84dc6a34b4720e0da978a);
        
    
        var popup_7c805ae9d92540b49cd325301abcf7f4 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_130e699c435649cab18733124b687afd = $(`<div id="html_130e699c435649cab18733124b687afd" style="width: 100.0%; height: 100.0%;">Blue Mountain Jamaican Restaurant, 884 Morton St, Boston, MA 02126</div>`)[0];
            popup_7c805ae9d92540b49cd325301abcf7f4.setContent(html_130e699c435649cab18733124b687afd);
        

        marker_8f7e15ffe4fa4177b5bc15fc40ca4fd3.bindPopup(popup_7c805ae9d92540b49cd325301abcf7f4)
        ;

        
    
    
            var marker_09ff9469c1c443a49d32ded2b2b9edae = L.marker(
                [42.296345624999994, -71.08766490000001],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_f7089b16f45c486b98a18526e156e4bb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_09ff9469c1c443a49d32ded2b2b9edae.setIcon(icon_f7089b16f45c486b98a18526e156e4bb);
        
    
        var popup_49fc7a6e7bd64294a75764b27c9a1ad2 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_c23dbcbc2c26431698c64d36d7bbdf22 = $(`<div id="html_c23dbcbc2c26431698c64d36d7bbdf22" style="width: 100.0%; height: 100.0%;">Country Kitchen, 838 Blue Hill Ave, Boston, MA 02124</div>`)[0];
            popup_49fc7a6e7bd64294a75764b27c9a1ad2.setContent(html_c23dbcbc2c26431698c64d36d7bbdf22);
        

        marker_09ff9469c1c443a49d32ded2b2b9edae.bindPopup(popup_49fc7a6e7bd64294a75764b27c9a1ad2)
        ;

        
    
    
            var marker_0a033ec5f0d14d49be21086b995812f0 = L.marker(
                [42.28928815524619, -71.07283851980753],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_e498a29a52a545c0b9a11ccbfab1240c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_0a033ec5f0d14d49be21086b995812f0.setIcon(icon_e498a29a52a545c0b9a11ccbfab1240c);
        
    
        var popup_2fed982988834506a161a917dcb1d9f3 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_82f35b5b296b455fa82644c92953c870 = $(`<div id="html_82f35b5b296b455fa82644c92953c870" style="width: 100.0%; height: 100.0%;">Taste of Eden, 38 Norfolk Street, Boston, MA 02124</div>`)[0];
            popup_2fed982988834506a161a917dcb1d9f3.setContent(html_82f35b5b296b455fa82644c92953c870);
        

        marker_0a033ec5f0d14d49be21086b995812f0.bindPopup(popup_2fed982988834506a161a917dcb1d9f3)
        ;

        
    
    
            var marker_2bdd2e655be9430e8a03496e552216b4 = L.marker(
                [42.30461425, -71.07939625],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_55755ea65c6947c1980fc43ed5d6bfab = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_2bdd2e655be9430e8a03496e552216b4.setIcon(icon_55755ea65c6947c1980fc43ed5d6bfab);
        
    
        var popup_9097a6cfb31b43bab431dfbc3598d1e7 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_a6970752a37f4a2eac4e03cd9e872373 = $(`<div id="html_a6970752a37f4a2eac4e03cd9e872373" style="width: 100.0%; height: 100.0%;">Murl&#39;s Kitchen, 143 Washington St, Dorchester, MA 02121</div>`)[0];
            popup_9097a6cfb31b43bab431dfbc3598d1e7.setContent(html_a6970752a37f4a2eac4e03cd9e872373);
        

        marker_2bdd2e655be9430e8a03496e552216b4.bindPopup(popup_9097a6cfb31b43bab431dfbc3598d1e7)
        ;

        
    
    
            var marker_74967eb516394321a52a9652a11428a0 = L.marker(
                [42.32909827693212, -71.08481936530762],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_12efc833afd8435dbfdac2cf57ce5740 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_74967eb516394321a52a9652a11428a0.setIcon(icon_12efc833afd8435dbfdac2cf57ce5740);
        
    
        var popup_c166610b13034ad7bccf4047ceafb51f = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_ab2b5184d8aa40428f5707875513937c = $(`<div id="html_ab2b5184d8aa40428f5707875513937c" style="width: 100.0%; height: 100.0%;">Silver Slipper Restaurant, 2387 Washington St, Roxbury, MA 02119</div>`)[0];
            popup_c166610b13034ad7bccf4047ceafb51f.setContent(html_ab2b5184d8aa40428f5707875513937c);
        

        marker_74967eb516394321a52a9652a11428a0.bindPopup(popup_c166610b13034ad7bccf4047ceafb51f)
        ;

        
    
    
            var marker_845021c5bcb946f5a4228b259f66818a = L.marker(
                [42.3419062, -71.083346],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_5288cc20fcde4a549a07184d6eb82794 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_845021c5bcb946f5a4228b259f66818a.setIcon(icon_5288cc20fcde4a549a07184d6eb82794);
        
    
        var popup_ed8350da800940c09b848f933311df43 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_e34b2a1d26a341ce818544e88dcfe37c = $(`<div id="html_e34b2a1d26a341ce818544e88dcfe37c" style="width: 100.0%; height: 100.0%;">Farmer Horse Coffee, 374 Massachusetts Ave, Boston, MA 02115</div>`)[0];
            popup_ed8350da800940c09b848f933311df43.setContent(html_e34b2a1d26a341ce818544e88dcfe37c);
        

        marker_845021c5bcb946f5a4228b259f66818a.bindPopup(popup_ed8350da800940c09b848f933311df43)
        ;

        
    
    
            var marker_02a8f2c87a22431d8dcc1c7b1a1ba83c = L.marker(
                [42.25638223230832, -71.12043229045054],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_b00a32d5bb5c495dba84c6a1a674529c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_02a8f2c87a22431d8dcc1c7b1a1ba83c.setIcon(icon_b00a32d5bb5c495dba84c6a1a674529c);
        
    
        var popup_507cce19f90e46c491735f2f91421374 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_16cad7a33db0460e9801b85e2aae90d0 = $(`<div id="html_16cad7a33db0460e9801b85e2aae90d0" style="width: 100.0%; height: 100.0%;">Farah&#39;s Café , 1158 River St, Boston, MA 02136</div>`)[0];
            popup_507cce19f90e46c491735f2f91421374.setContent(html_16cad7a33db0460e9801b85e2aae90d0);
        

        marker_02a8f2c87a22431d8dcc1c7b1a1ba83c.bindPopup(popup_507cce19f90e46c491735f2f91421374)
        ;

        
    
    
            var marker_f28e53660b884bb4a0ccb5824d967f82 = L.marker(
                [42.2953134402934, -71.08760276460016],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_fa5e3c937cf74b059882ff6dc275c724 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_f28e53660b884bb4a0ccb5824d967f82.setIcon(icon_fa5e3c937cf74b059882ff6dc275c724);
        
    
        var popup_172f6025cd084a8492b42f2266b9cbc1 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_b670db0889b84fb5b78f1a41552f15a5 = $(`<div id="html_b670db0889b84fb5b78f1a41552f15a5" style="width: 100.0%; height: 100.0%;">Natif Natal, 830 Blue Hill Ave, Boston, MA 02124</div>`)[0];
            popup_172f6025cd084a8492b42f2266b9cbc1.setContent(html_b670db0889b84fb5b78f1a41552f15a5);
        

        marker_f28e53660b884bb4a0ccb5824d967f82.bindPopup(popup_172f6025cd084a8492b42f2266b9cbc1)
        ;

        
    
    
            var marker_00f650f3fce14208948d0c01e0fb437a = L.marker(
                [42.287086625, -71.090711875],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_583ff1dca5e14befbd0f11bac944b11c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_00f650f3fce14208948d0c01e0fb437a.setIcon(icon_583ff1dca5e14befbd0f11bac944b11c);
        
    
        var popup_506d0537cd7d4cc3beb7327c77158698 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_dcf8aa4823b0462cb0aec8f6322832a0 = $(`<div id="html_dcf8aa4823b0462cb0aec8f6322832a0" style="width: 100.0%; height: 100.0%;">Nu Flav Restaurant, 1100 Blue Hill Ave, Boston, MA 02124</div>`)[0];
            popup_506d0537cd7d4cc3beb7327c77158698.setContent(html_dcf8aa4823b0462cb0aec8f6322832a0);
        

        marker_00f650f3fce14208948d0c01e0fb437a.bindPopup(popup_506d0537cd7d4cc3beb7327c77158698)
        ;

        
    
    
            var marker_74a3356600684ff3a1c032bc2d83de40 = L.marker(
                [42.303566, -71.0787986],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_458ac853e16546569a5b5527bafae9db = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_74a3356600684ff3a1c032bc2d83de40.setIcon(icon_458ac853e16546569a5b5527bafae9db);
        
    
        var popup_75341529137f490ca61cab8c08f175fd = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_dc7a94d5270b44c496889337e75b45b7 = $(`<div id="html_dc7a94d5270b44c496889337e75b45b7" style="width: 100.0%; height: 100.0%;">Island Style Jamaican Restaurant, 183 Washington St, Boston, MA 02121</div>`)[0];
            popup_75341529137f490ca61cab8c08f175fd.setContent(html_dc7a94d5270b44c496889337e75b45b7);
        

        marker_74a3356600684ff3a1c032bc2d83de40.bindPopup(popup_75341529137f490ca61cab8c08f175fd)
        ;

        
    
    
            var marker_e6dd257919a948bbb2e6c27797b8271f = L.marker(
                [42.2671715, -71.0944404],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_fa2b7884b09d4c76ac9ce96e09cb0540 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_e6dd257919a948bbb2e6c27797b8271f.setIcon(icon_fa2b7884b09d4c76ac9ce96e09cb0540);
        
    
        var popup_0f05a916e8b348c3a254aefa0726df32 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_fac145e3c4c74758b53ca6edd9cff1bc = $(`<div id="html_fac145e3c4c74758b53ca6edd9cff1bc" style="width: 100.0%; height: 100.0%;">Right Taste Jamaican Restaurant, 522 River St, Mattapan, MA 02126</div>`)[0];
            popup_0f05a916e8b348c3a254aefa0726df32.setContent(html_fac145e3c4c74758b53ca6edd9cff1bc);
        

        marker_e6dd257919a948bbb2e6c27797b8271f.bindPopup(popup_0f05a916e8b348c3a254aefa0726df32)
        ;

        
    
    
            var marker_94cd8f90077c41b39444314ae0e8b3e8 = L.marker(
                [42.330308450000004, -71.05289748125072],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_c5704120fdbc42a3963aecb9167f5d67 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_94cd8f90077c41b39444314ae0e8b3e8.setIcon(icon_c5704120fdbc42a3963aecb9167f5d67);
        
    
        var popup_5d54f2c100494a4fa599b86026fda022 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_3460a537d7b442148da13e1f8f46f9c8 = $(`<div id="html_3460a537d7b442148da13e1f8f46f9c8" style="width: 100.0%; height: 100.0%;">On The Edge Nutrition, 283 Old Colony Ave,, Boston, MA 02127</div>`)[0];
            popup_5d54f2c100494a4fa599b86026fda022.setContent(html_3460a537d7b442148da13e1f8f46f9c8);
        

        marker_94cd8f90077c41b39444314ae0e8b3e8.bindPopup(popup_5d54f2c100494a4fa599b86026fda022)
        ;

        
    
    
            var marker_776758987e8344359b4ba488238fff0f = L.marker(
                [42.3287383, -71.0854775],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_126c183600bd4432aa72cb9856deb9ad = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_776758987e8344359b4ba488238fff0f.setIcon(icon_126c183600bd4432aa72cb9856deb9ad);
        
    
        var popup_240653843d98465a8c88d798ba2fac7c = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_96be70f610d94c37847289faac4256e8 = $(`<div id="html_96be70f610d94c37847289faac4256e8" style="width: 100.0%; height: 100.0%;">Millenium Restaurant, 3094 Washington St, Boston, MA 02119</div>`)[0];
            popup_240653843d98465a8c88d798ba2fac7c.setContent(html_96be70f610d94c37847289faac4256e8);
        

        marker_776758987e8344359b4ba488238fff0f.bindPopup(popup_240653843d98465a8c88d798ba2fac7c)
        ;

        
    
    
            var marker_fbf1b787eeeb49fbba02aaa581d55c31 = L.marker(
                [42.332978, -71.07293954545455],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_2847efe3c45e490da1a89bafd976df32 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_fbf1b787eeeb49fbba02aaa581d55c31.setIcon(icon_2847efe3c45e490da1a89bafd976df32);
        
    
        var popup_76a4d017354641e180e79199153c296d = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_5c4d39400c844c62893343f408c28ccc = $(`<div id="html_5c4d39400c844c62893343f408c28ccc" style="width: 100.0%; height: 100.0%;">Doña Habana Restaurant, 811 Massachusetts Ave, Boston, MA 02118</div>`)[0];
            popup_76a4d017354641e180e79199153c296d.setContent(html_5c4d39400c844c62893343f408c28ccc);
        

        marker_fbf1b787eeeb49fbba02aaa581d55c31.bindPopup(popup_76a4d017354641e180e79199153c296d)
        ;

        
    
    
            var marker_2b563852f2ab4bd9be7f564597cde899 = L.marker(
                [42.319158, -71.077639],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_cc4c6d175ab740acabcc769a40800133 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_2b563852f2ab4bd9be7f564597cde899.setIcon(icon_cc4c6d175ab740acabcc769a40800133);
        
    
        var popup_1a0a9ea85572476396d23a7363e302f7 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_a80c7545874242f79a5aaf6807ce8eed = $(`<div id="html_a80c7545874242f79a5aaf6807ce8eed" style="width: 100.0%; height: 100.0%;">Merengue Restaurant, 160 Blue Hill Avenue, Boston, MA 02125</div>`)[0];
            popup_1a0a9ea85572476396d23a7363e302f7.setContent(html_a80c7545874242f79a5aaf6807ce8eed);
        

        marker_2b563852f2ab4bd9be7f564597cde899.bindPopup(popup_1a0a9ea85572476396d23a7363e302f7)
        ;

        
    
    
            var marker_615e474052fd421eb56c3037c395d6b8 = L.marker(
                [42.342451000000004, -71.08431733333333],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_ad47c46e3d8c430a94c46976de246d4b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_615e474052fd421eb56c3037c395d6b8.setIcon(icon_ad47c46e3d8c430a94c46976de246d4b);
        
    
        var popup_87ef578b377e43c683ae6a27940bf27a = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_98da87d9ab7544159a9e0c119d19c480 = $(`<div id="html_98da87d9ab7544159a9e0c119d19c480" style="width: 100.0%; height: 100.0%;">Lucy Ethiopian Cafe, 334 Massachusetts Ave, Boston, MA 02115</div>`)[0];
            popup_87ef578b377e43c683ae6a27940bf27a.setContent(html_98da87d9ab7544159a9e0c119d19c480);
        

        marker_615e474052fd421eb56c3037c395d6b8.bindPopup(popup_87ef578b377e43c683ae6a27940bf27a)
        ;

        
    
    
            var marker_728b9c01f8544891bc4395f378db6073 = L.marker(
                [42.292816, -71.088516],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_a96d808884384e39b966030a915f2f3a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_728b9c01f8544891bc4395f378db6073.setIcon(icon_a96d808884384e39b966030a915f2f3a);
        
    
        var popup_2d1ad769ff824f3199c25e60b4ab7cee = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_10d47dfea8dc4533b669bf574103dd52 = $(`<div id="html_10d47dfea8dc4533b669bf574103dd52" style="width: 100.0%; height: 100.0%;">Wingz and Tingz, 388 Blue Hill Ave, Boston, MA 02124</div>`)[0];
            popup_2d1ad769ff824f3199c25e60b4ab7cee.setContent(html_10d47dfea8dc4533b669bf574103dd52);
        

        marker_728b9c01f8544891bc4395f378db6073.bindPopup(popup_2d1ad769ff824f3199c25e60b4ab7cee)
        ;

        
    
    
            var marker_a4559856e945457887481ea008a28b77 = L.marker(
                [42.3487374, -71.039117],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_6291c3b1e7ca43649f8d281d1b9e87c9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_a4559856e945457887481ea008a28b77.setIcon(icon_6291c3b1e7ca43649f8d281d1b9e87c9);
        
    
        var popup_7d866c8d2026461e90434844a7206c85 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_8e74eb5a813a4379bd55470693c5fa88 = $(`<div id="html_8e74eb5a813a4379bd55470693c5fa88" style="width: 100.0%; height: 100.0%;">Larry J&#39;s BBQ Cafe, 600 D St, Boston, MA 02151</div>`)[0];
            popup_7d866c8d2026461e90434844a7206c85.setContent(html_8e74eb5a813a4379bd55470693c5fa88);
        

        marker_a4559856e945457887481ea008a28b77.bindPopup(popup_7d866c8d2026461e90434844a7206c85)
        ;

        
    
    
            var marker_dc59b58f595641dda7650c841328ce08 = L.marker(
                [42.352320828185405, -71.12418780449352],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_5e5e968c96504e528b48a9c697a5570f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_dc59b58f595641dda7650c841328ce08.setIcon(icon_5e5e968c96504e528b48a9c697a5570f);
        
    
        var popup_3ddab04669834e9e831ebbacf3fec9fe = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_cb778ecc43b14cca89d3163da592642a = $(`<div id="html_cb778ecc43b14cca89d3163da592642a" style="width: 100.0%; height: 100.0%;">Rhythm &#39;n Wraps, 1096 Commonwealth Avenue, Boston, MA 02134</div>`)[0];
            popup_3ddab04669834e9e831ebbacf3fec9fe.setContent(html_cb778ecc43b14cca89d3163da592642a);
        

        marker_dc59b58f595641dda7650c841328ce08.bindPopup(popup_3ddab04669834e9e831ebbacf3fec9fe)
        ;

        
    
    
            var marker_ac5c17ded5b74c1785dcb9b2e04d43b8 = L.marker(
                [42.07303381818182, -71.01872281818181],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_740d705e9eb5463aa539531222d99ed6 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_ac5c17ded5b74c1785dcb9b2e04d43b8.setIcon(icon_740d705e9eb5463aa539531222d99ed6);
        
    
        var popup_566fecc23c894e49b11ed813548cc8b4 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_8d7678e83157459386a9803da92852e4 = $(`<div id="html_8d7678e83157459386a9803da92852e4" style="width: 100.0%; height: 100.0%;">JJ&#39;s Caffe, 610 N Main St., Brockton, MA 02301</div>`)[0];
            popup_566fecc23c894e49b11ed813548cc8b4.setContent(html_8d7678e83157459386a9803da92852e4);
        

        marker_ac5c17ded5b74c1785dcb9b2e04d43b8.bindPopup(popup_566fecc23c894e49b11ed813548cc8b4)
        ;

        
    
    
            var marker_4cdca5e60a8849cb9ed412b349b72f88 = L.marker(
                [46.3144754, 11.0480288],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_47c63289e0a84c8f8328fd4e0e43ba09 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_4cdca5e60a8849cb9ed412b349b72f88.setIcon(icon_47c63289e0a84c8f8328fd4e0e43ba09);
        
    
        var popup_26fb0c8a8e49400e9c402445822cfa73 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_624ab6d1add2470694cba73908015b22 = $(`<div id="html_624ab6d1add2470694cba73908015b22" style="width: 100.0%; height: 100.0%;">Luanda, nan</div>`)[0];
            popup_26fb0c8a8e49400e9c402445822cfa73.setContent(html_624ab6d1add2470694cba73908015b22);
        

        marker_4cdca5e60a8849cb9ed412b349b72f88.bindPopup(popup_26fb0c8a8e49400e9c402445822cfa73)
        ;

        
    
    
            var marker_ec02ab37c0d04daab8f75b1e42cb09db = L.marker(
                [42.074819800142286, -71.04151337029444],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_b10001692c14470ca57958ba9743a84b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_ec02ab37c0d04daab8f75b1e42cb09db.setIcon(icon_b10001692c14470ca57958ba9743a84b);
        
    
        var popup_b3c98f18fd204fb1905535367369a35d = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_72fa35bd16fb45e09351d027fccbcc2b = $(`<div id="html_72fa35bd16fb45e09351d027fccbcc2b" style="width: 100.0%; height: 100.0%;">Flava Jamaica, 21 Torrey St., Brockton, MA 00301</div>`)[0];
            popup_b3c98f18fd204fb1905535367369a35d.setContent(html_72fa35bd16fb45e09351d027fccbcc2b);
        

        marker_ec02ab37c0d04daab8f75b1e42cb09db.bindPopup(popup_b3c98f18fd204fb1905535367369a35d)
        ;

        
    
    
            var marker_998295241a684f80b940047fe4530777 = L.marker(
                [42.3664123, -71.1050773],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_1892f94098704f279816a7712cb16fe9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_998295241a684f80b940047fe4530777.setIcon(icon_1892f94098704f279816a7712cb16fe9);
        
    
        var popup_62fae6a6e7964e50a7caeb345000a272 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_2b1503a044ec45b6b67a691cb23da2a6 = $(`<div id="html_2b1503a044ec45b6b67a691cb23da2a6" style="width: 100.0%; height: 100.0%;">Asmara Restaurant, 739 Massachusetts Ave, Cambridge, MA 02139</div>`)[0];
            popup_62fae6a6e7964e50a7caeb345000a272.setContent(html_2b1503a044ec45b6b67a691cb23da2a6);
        

        marker_998295241a684f80b940047fe4530777.bindPopup(popup_62fae6a6e7964e50a7caeb345000a272)
        ;

        
    
    
            var marker_58d1c5e988e548ecba64f663ab71cba8 = L.marker(
                [42.3609802, -71.1009966],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_be040eadb2474f40a8a7d8db05099293 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_58d1c5e988e548ecba64f663ab71cba8.setIcon(icon_be040eadb2474f40a8a7d8db05099293);
        
    
        var popup_bd8924d05f234d9dad09c14c201fd021 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_1ccb245fe926465c916e5455eb988bb1 = $(`<div id="html_1ccb245fe926465c916e5455eb988bb1" style="width: 100.0%; height: 100.0%;">Bytes Cafe, 64 Sidney St #1, Cambridge, MA 02139</div>`)[0];
            popup_bd8924d05f234d9dad09c14c201fd021.setContent(html_1ccb245fe926465c916e5455eb988bb1);
        

        marker_58d1c5e988e548ecba64f663ab71cba8.bindPopup(popup_bd8924d05f234d9dad09c14c201fd021)
        ;

        
    
    
            var marker_3f8255d465d749e3808dc00a953de4f8 = L.marker(
                [42.39672493333333, -71.12971633333333],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_f4e7561f36354491b138b836efce8fcb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_3f8255d465d749e3808dc00a953de4f8.setIcon(icon_f4e7561f36354491b138b836efce8fcb);
        
    
        var popup_17c6ae5505c14881a942fffd9cfb568d = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_9b3b7b04f7bb4f20b20ecf74d92109bc = $(`<div id="html_9b3b7b04f7bb4f20b20ecf74d92109bc" style="width: 100.0%; height: 100.0%;">Sheger Cafe and Ethiopian Restaurant LLC, 2376 Massachusetts Avenue, Cambridge, MA 02140</div>`)[0];
            popup_17c6ae5505c14881a942fffd9cfb568d.setContent(html_9b3b7b04f7bb4f20b20ecf74d92109bc);
        

        marker_3f8255d465d749e3808dc00a953de4f8.bindPopup(popup_17c6ae5505c14881a942fffd9cfb568d)
        ;

        
    
    
            var marker_be7b512a1c734cd0a98134cc49eb51e9 = L.marker(
                [42.366207, -71.095589],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_805dd8c6d19046fc8f353a5fd540dadc = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_be7b512a1c734cd0a98134cc49eb51e9.setIcon(icon_805dd8c6d19046fc8f353a5fd540dadc);
        
    
        var popup_04bca3e3a9e94e1890f864fd7028b130 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_6835d9b6ad75415e8327c505623c4987 = $(`<div id="html_6835d9b6ad75415e8327c505623c4987" style="width: 100.0%; height: 100.0%;">Izzy&#39;s Restaurant &amp; Sub Shop, 169 Harvard St, Cambridge, MA 02139</div>`)[0];
            popup_04bca3e3a9e94e1890f864fd7028b130.setContent(html_6835d9b6ad75415e8327c505623c4987);
        

        marker_be7b512a1c734cd0a98134cc49eb51e9.bindPopup(popup_04bca3e3a9e94e1890f864fd7028b130)
        ;

        
    
    
            var marker_e86d90ff9a93425db2528d360616ab09 = L.marker(
                [42.3841278, -71.1196974],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_82f3121f1a68487488169ce5f3a6fd4f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_e86d90ff9a93425db2528d360616ab09.setIcon(icon_82f3121f1a68487488169ce5f3a6fd4f);
        
    
        var popup_dd52e8545e50464d99c808d8a932f18e = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_1eb82dfca8c148b6a7c4ea3ca8b56805 = $(`<div id="html_1eb82dfca8c148b6a7c4ea3ca8b56805" style="width: 100.0%; height: 100.0%;">Baraka Cafe, 1728 Massachusetts Avenue, CAMBRIDGE, MA 02138</div>`)[0];
            popup_dd52e8545e50464d99c808d8a932f18e.setContent(html_1eb82dfca8c148b6a7c4ea3ca8b56805);
        

        marker_e86d90ff9a93425db2528d360616ab09.bindPopup(popup_dd52e8545e50464d99c808d8a932f18e)
        ;

        
    
    
            var marker_3f2157b894224289a4e1bf25b533c77e = L.marker(
                [42.3630585, -71.11162477738836],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_abaf452c6c624c109746af9a81a9e8e7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_3f2157b894224289a4e1bf25b533c77e.setIcon(icon_abaf452c6c624c109746af9a81a9e8e7);
        
    
        var popup_51d2c78cbabe4dc3b2040c8e3ce74533 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_6b408f878c934b97ac9ea039c2b45b06 = $(`<div id="html_6b408f878c934b97ac9ea039c2b45b06" style="width: 100.0%; height: 100.0%;">The Coast Café, 233 River Street, Cambridge, MA 02139</div>`)[0];
            popup_51d2c78cbabe4dc3b2040c8e3ce74533.setContent(html_6b408f878c934b97ac9ea039c2b45b06);
        

        marker_3f2157b894224289a4e1bf25b533c77e.bindPopup(popup_51d2c78cbabe4dc3b2040c8e3ce74533)
        ;

        
    
    
            var marker_fc0dc4a90acb47c78b55be1365af4304 = L.marker(
                [42.372434399999996, -71.11910280000001],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_34f2eea9285f4a88ad2bbf58ae06dbd0 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_fc0dc4a90acb47c78b55be1365af4304.setIcon(icon_34f2eea9285f4a88ad2bbf58ae06dbd0);
        
    
        var popup_592009bb49be46e8b01215522cbad5d4 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_900f7d385ba34d0e9d1c641c9cc40ebb = $(`<div id="html_900f7d385ba34d0e9d1c641c9cc40ebb" style="width: 100.0%; height: 100.0%;">Oggi Gourmet, 30 Dunster Street, Cambridge, MA 02138</div>`)[0];
            popup_592009bb49be46e8b01215522cbad5d4.setContent(html_900f7d385ba34d0e9d1c641c9cc40ebb);
        

        marker_fc0dc4a90acb47c78b55be1365af4304.bindPopup(popup_592009bb49be46e8b01215522cbad5d4)
        ;

        
    
    
            var marker_bfe1abddbe4e4cd9925f40ae4e516aa7 = L.marker(
                [46.3144754, 11.0480288],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_bc10266521e74a8bbbae40ad5cd2a06f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_bfe1abddbe4e4cd9925f40ae4e516aa7.setIcon(icon_bc10266521e74a8bbbae40ad5cd2a06f);
        
    
        var popup_8bceade02a454c229d975aaac00d1d36 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_3d42e70e154f4802b24e9dd2ffdf6f28 = $(`<div id="html_3d42e70e154f4802b24e9dd2ffdf6f28" style="width: 100.0%; height: 100.0%;">The Little Crêpe Café, nan</div>`)[0];
            popup_8bceade02a454c229d975aaac00d1d36.setContent(html_3d42e70e154f4802b24e9dd2ffdf6f28);
        

        marker_bfe1abddbe4e4cd9925f40ae4e516aa7.bindPopup(popup_8bceade02a454c229d975aaac00d1d36)
        ;

        
    
    
            var marker_bf8e6517ce314a28bf792d6f2f724cbf = L.marker(
                [42.29926643329872, -71.06033244762894],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_8b6c3689e949496e8600a11774e0f0e9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_bf8e6517ce314a28bf792d6f2f724cbf.setIcon(icon_8b6c3689e949496e8600a11774e0f0e9);
        
    
        var popup_3c1abdc3804444a6a61c97378a944277 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_e15ae6ce47df425582601a7b0d36062b = $(`<div id="html_e15ae6ce47df425582601a7b0d36062b" style="width: 100.0%; height: 100.0%;">Antonio&#39;s Pizzeria , 1508 Dorchester Ave, Dorchester, MA 02122</div>`)[0];
            popup_3c1abdc3804444a6a61c97378a944277.setContent(html_e15ae6ce47df425582601a7b0d36062b);
        

        marker_bf8e6517ce314a28bf792d6f2f724cbf.bindPopup(popup_3c1abdc3804444a6a61c97378a944277)
        ;

        
    
    
            var marker_4717715326364923b992f6f16f2d6ed5 = L.marker(
                [42.306916, -71.06641185714285],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_0a9fbf77e0044f6a9ddf36a8c71d019b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_4717715326364923b992f6f16f2d6ed5.setIcon(icon_0a9fbf77e0044f6a9ddf36a8c71d019b);
        
    
        var popup_a1e3b31c6d7047f8873c3dbf8f6c7d66 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_6fc88edbb33143bea6ad8f346d283f46 = $(`<div id="html_6fc88edbb33143bea6ad8f346d283f46" style="width: 100.0%; height: 100.0%;">Cesaria, 266 Bowdoin St, Dorchester, MA 02122</div>`)[0];
            popup_a1e3b31c6d7047f8873c3dbf8f6c7d66.setContent(html_6fc88edbb33143bea6ad8f346d283f46);
        

        marker_4717715326364923b992f6f16f2d6ed5.bindPopup(popup_a1e3b31c6d7047f8873c3dbf8f6c7d66)
        ;

        
    
    
            var marker_3046f245aa104915ae5f122ccbce97c1 = L.marker(
                [42.281812333333335, -71.07129822222223],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_8bb69962d38449bf95fae56caa612fc2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_3046f245aa104915ae5f122ccbce97c1.setIcon(icon_8bb69962d38449bf95fae56caa612fc2);
        
    
        var popup_e7a08ea1c85c4d15a257d3358ff14801 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_b34998c484994127873632a6b2b86294 = $(`<div id="html_b34998c484994127873632a6b2b86294" style="width: 100.0%; height: 100.0%;">Irie Jamaican Style Restaurant, 855 Washington St, Dorchester Center, MA 02124</div>`)[0];
            popup_e7a08ea1c85c4d15a257d3358ff14801.setContent(html_b34998c484994127873632a6b2b86294);
        

        marker_3046f245aa104915ae5f122ccbce97c1.bindPopup(popup_e7a08ea1c85c4d15a257d3358ff14801)
        ;

        
    
    
            var marker_c044d6a970cd46278013d5b1994108b6 = L.marker(
                [42.36579555555556, -71.02918677777778],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_13b4e877906a45bdb44d32c3cb206df1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_c044d6a970cd46278013d5b1994108b6.setIcon(icon_13b4e877906a45bdb44d32c3cb206df1);
        
    
        var popup_3af6ffc4cba94a76ab86c433546c602d = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_3f52862c86db473887034768980346af = $(`<div id="html_3f52862c86db473887034768980346af" style="width: 100.0%; height: 100.0%;">Tawakal Halal Cafe, 389 Maverick St, Boston, MA 02128</div>`)[0];
            popup_3af6ffc4cba94a76ab86c433546c602d.setContent(html_3f52862c86db473887034768980346af);
        

        marker_c044d6a970cd46278013d5b1994108b6.bindPopup(popup_3af6ffc4cba94a76ab86c433546c602d)
        ;

        
    
    
            var marker_0a9a1dc038874d27bf4d3325a7cdc496 = L.marker(
                [42.3017344, -71.4012664],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_99ea9346ebe64fa5911bdeb740a6dc33 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_0a9a1dc038874d27bf4d3325a7cdc496.setIcon(icon_99ea9346ebe64fa5911bdeb740a6dc33);
        
    
        var popup_e175e1a4c534479db75162942a820aa8 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_f49ffa4338af41df9566b4a11a6eb429 = $(`<div id="html_f49ffa4338af41df9566b4a11a6eb429" style="width: 100.0%; height: 100.0%;">Nzuko, 341 Cochituate Road, Framingham, MA 01701</div>`)[0];
            popup_e175e1a4c534479db75162942a820aa8.setContent(html_f49ffa4338af41df9566b4a11a6eb429);
        

        marker_0a9a1dc038874d27bf4d3325a7cdc496.bindPopup(popup_e175e1a4c534479db75162942a820aa8)
        ;

        
    
    
            var marker_0acc3643bc6a4fe6936b063a96bb990c = L.marker(
                [42.070858400000006, -71.42380990000001],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_a26f6cd268cc4ec3b9eefd3acfb71988 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_0acc3643bc6a4fe6936b063a96bb990c.setIcon(icon_a26f6cd268cc4ec3b9eefd3acfb71988);
        
    
        var popup_ab340f2651414d3b925fcaa439a74d61 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_b6cc99be94d04d77bf02cf07f7f553c6 = $(`<div id="html_b6cc99be94d04d77bf02cf07f7f553c6" style="width: 100.0%; height: 100.0%;">67 Degrees Brewing, 158 Grove St, Franklin, MA  </div>`)[0];
            popup_ab340f2651414d3b925fcaa439a74d61.setContent(html_b6cc99be94d04d77bf02cf07f7f553c6);
        

        marker_0acc3643bc6a4fe6936b063a96bb990c.bindPopup(popup_ab340f2651414d3b925fcaa439a74d61)
        ;

        
    
    
            var marker_85b554f861df4b4d930830c89d0e7195 = L.marker(
                [42.3094644, -71.1043642],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_ac8fd3f95eac44e9a62ad7412aa0715b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_85b554f861df4b4d930830c89d0e7195.setIcon(icon_ac8fd3f95eac44e9a62ad7412aa0715b);
        
    
        var popup_dae3bf79bc88478f9ffdf96c9db0f8dd = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_9bc34bbc40a942258ec32ba118c0bea9 = $(`<div id="html_9bc34bbc40a942258ec32ba118c0bea9" style="width: 100.0%; height: 100.0%;">Exodus Bagels, 3346 Washington St, Boston, MA 02130</div>`)[0];
            popup_dae3bf79bc88478f9ffdf96c9db0f8dd.setContent(html_9bc34bbc40a942258ec32ba118c0bea9);
        

        marker_85b554f861df4b4d930830c89d0e7195.bindPopup(popup_dae3bf79bc88478f9ffdf96c9db0f8dd)
        ;

        
    
    
            var marker_61afd31849d248698204fe8bdc5db760 = L.marker(
                [42.3047401, -71.1247301],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_4d30ffdc66ed4d2f82f058bef89dd5ea = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_61afd31849d248698204fe8bdc5db760.setIcon(icon_4d30ffdc66ed4d2f82f058bef89dd5ea);
        
    
        var popup_6db35d849c444eaf986cd60b28ff713a = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_1e8f70f930a94114a1e207b3307cb3d5 = $(`<div id="html_1e8f70f930a94114a1e207b3307cb3d5" style="width: 100.0%; height: 100.0%;">Blue Nile Restaurant, 389 Centre St. Jamaica Plain, nan, MA 02130</div>`)[0];
            popup_6db35d849c444eaf986cd60b28ff713a.setContent(html_1e8f70f930a94114a1e207b3307cb3d5);
        

        marker_61afd31849d248698204fe8bdc5db760.bindPopup(popup_6db35d849c444eaf986cd60b28ff713a)
        ;

        
    
    
            var marker_21394c41549643e4beabc91f9f6cad6b = L.marker(
                [42.3228145, -71.101827],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_f856552c956c41d2ae1032ae05ce5353 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_21394c41549643e4beabc91f9f6cad6b.setIcon(icon_f856552c956c41d2ae1032ae05ce5353);
        
    
        var popup_5f904b6308d04bd19601bb32778215ba = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_fd239bd9854543fa9cac41b23b8485b5 = $(`<div id="html_fd239bd9854543fa9cac41b23b8485b5" style="width: 100.0%; height: 100.0%;">Yelu&#39;s, 284 Centre St, Jamaica Plain, MA 02130</div>`)[0];
            popup_5f904b6308d04bd19601bb32778215ba.setContent(html_fd239bd9854543fa9cac41b23b8485b5);
        

        marker_21394c41549643e4beabc91f9f6cad6b.bindPopup(popup_5f904b6308d04bd19601bb32778215ba)
        ;

        
    
    
            var marker_fd43e40d8a25495fb61edbdb72a3a643 = L.marker(
                [42.321376, -71.110085],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_a73610571ec240d287f3aa27337be4bf = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_fd43e40d8a25495fb61edbdb72a3a643.setIcon(icon_a73610571ec240d287f3aa27337be4bf);
        
    
        var popup_8fd3cb8cdc2e433589cfff46e7525a5d = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_3220fc705e224651a238d0c968f9658d = $(`<div id="html_3220fc705e224651a238d0c968f9658d" style="width: 100.0%; height: 100.0%;">Pikalo Restaurant, 378 Centre St, Boston, MA 02130</div>`)[0];
            popup_8fd3cb8cdc2e433589cfff46e7525a5d.setContent(html_3220fc705e224651a238d0c968f9658d);
        

        marker_fd43e40d8a25495fb61edbdb72a3a643.bindPopup(popup_8fd3cb8cdc2e433589cfff46e7525a5d)
        ;

        
    
    
            var marker_fb2a5c1df96a450686d6b1622fd34bfb = L.marker(
                [42.301481083332305, -71.1122889166677],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_b50ba4c34aa1447ba9a1fdc47a56e661 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_fb2a5c1df96a450686d6b1622fd34bfb.setIcon(icon_b50ba4c34aa1447ba9a1fdc47a56e661);
        
    
        var popup_9f65385676ce480da1ed3a2c0f10b8d0 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_3c9477ff47944c7ab454540a3861f5b9 = $(`<div id="html_3c9477ff47944c7ab454540a3861f5b9" style="width: 100.0%; height: 100.0%;">Imani Massage, 3684 Washington Street, Boston, MA 02130</div>`)[0];
            popup_9f65385676ce480da1ed3a2c0f10b8d0.setContent(html_3c9477ff47944c7ab454540a3861f5b9);
        

        marker_fb2a5c1df96a450686d6b1622fd34bfb.bindPopup(popup_9f65385676ce480da1ed3a2c0f10b8d0)
        ;

        
    
    
            var marker_420c30ad9a634a75aae97862ca7b1c88 = L.marker(
                [42.3047401, -71.1247301],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_6f27701bedb04e7ba778c615447587f1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_420c30ad9a634a75aae97862ca7b1c88.setIcon(icon_6f27701bedb04e7ba778c615447587f1);
        
    
        var popup_0a4077bafcd84756833691caf2230ec8 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_e13c5c8a0bd143878f55baa5ea3afe86 = $(`<div id="html_e13c5c8a0bd143878f55baa5ea3afe86" style="width: 100.0%; height: 100.0%;">Ethiopian Cafe, 377 Centre St., Jamaica Plain, MA 02130</div>`)[0];
            popup_0a4077bafcd84756833691caf2230ec8.setContent(html_e13c5c8a0bd143878f55baa5ea3afe86);
        

        marker_420c30ad9a634a75aae97862ca7b1c88.bindPopup(popup_0a4077bafcd84756833691caf2230ec8)
        ;

        
    
    
            var marker_8a1d2f02b7544b78a03b88231c656954 = L.marker(
                [42.3229042, -71.0992479],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_624753df0fc7472cbfbbdd69d908d299 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_8a1d2f02b7544b78a03b88231c656954.setIcon(icon_624753df0fc7472cbfbbdd69d908d299);
        
    
        var popup_796b988441ad47fc8b06ab903c14a45b = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_d457e7eefd414302936589fedc17841f = $(`<div id="html_d457e7eefd414302936589fedc17841f" style="width: 100.0%; height: 100.0%;">Jamaica Mi Hungry, 225 Centre St, Boston, MA 02130</div>`)[0];
            popup_796b988441ad47fc8b06ab903c14a45b.setContent(html_d457e7eefd414302936589fedc17841f);
        

        marker_8a1d2f02b7544b78a03b88231c656954.bindPopup(popup_796b988441ad47fc8b06ab903c14a45b)
        ;

        
    
    
            var marker_2e65a66171c0415a92919be9bebe412f = L.marker(
                [42.460929, -70.95006],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_8ba536c7ad664db1b9cd3aef5024c934 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_2e65a66171c0415a92919be9bebe412f.setIcon(icon_8ba536c7ad664db1b9cd3aef5024c934);
        
    
        var popup_f19623ec459840e2b6d29b594802d920 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_880cc04952a041dda1a7b319a48494d6 = $(`<div id="html_880cc04952a041dda1a7b319a48494d6" style="width: 100.0%; height: 100.0%;">Jamaica&#39;s Flavor , 121 Pleasant St, Lynn, MA 01901</div>`)[0];
            popup_f19623ec459840e2b6d29b594802d920.setContent(html_880cc04952a041dda1a7b319a48494d6);
        

        marker_2e65a66171c0415a92919be9bebe412f.bindPopup(popup_f19623ec459840e2b6d29b594802d920)
        ;

        
    
    
            var marker_4a0ed361e2fc4afd9abdd08d267e263d = L.marker(
                [42.4679876, -70.95864440657522],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_cdadfc8260174b7ca2568c0d55067d4e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_4a0ed361e2fc4afd9abdd08d267e263d.setIcon(icon_cdadfc8260174b7ca2568c0d55067d4e);
        
    
        var popup_1050e829bcce42b5837f75e59120a09c = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_cf688a4653bf4f3d8a7d28d3a976a1fe = $(`<div id="html_cf688a4653bf4f3d8a7d28d3a976a1fe" style="width: 100.0%; height: 100.0%;">Rite Spice Caribbean, 532 Western Ave, Lynn, MA 01904</div>`)[0];
            popup_1050e829bcce42b5837f75e59120a09c.setContent(html_cf688a4653bf4f3d8a7d28d3a976a1fe);
        

        marker_4a0ed361e2fc4afd9abdd08d267e263d.bindPopup(popup_1050e829bcce42b5837f75e59120a09c)
        ;

        
    
    
            var marker_58902ef7aa44476ca5694d164ed300d0 = L.marker(
                [42.4238427, -71.0660252],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_eccd4773b79f4df9b9ad92a28688baf6 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_58902ef7aa44476ca5694d164ed300d0.setIcon(icon_eccd4773b79f4df9b9ad92a28688baf6);
        
    
        var popup_6d14995248f0434f88602ca79ac4d9c5 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_3f8799e414f746c6ad9e18a12e3291b0 = $(`<div id="html_3f8799e414f746c6ad9e18a12e3291b0" style="width: 100.0%; height: 100.0%;">Crazy Good Kitchen, 906 Eastern Ave, Malden, MA 02148</div>`)[0];
            popup_6d14995248f0434f88602ca79ac4d9c5.setContent(html_3f8799e414f746c6ad9e18a12e3291b0);
        

        marker_58902ef7aa44476ca5694d164ed300d0.bindPopup(popup_6d14995248f0434f88602ca79ac4d9c5)
        ;

        
    
    
            var marker_6ca40d98d351461381f0e84de3ab3f48 = L.marker(
                [42.277580977411475, -71.09324400118888],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_063e612708d9422c8e5c765260b9da52 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_6ca40d98d351461381f0e84de3ab3f48.setIcon(icon_063e612708d9422c8e5c765260b9da52);
        
    
        var popup_b004fa3d072e4ff1a3cd6df0eaa025b5 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_42e2bba621d94003b868750035fedf9f = $(`<div id="html_42e2bba621d94003b868750035fedf9f" style="width: 100.0%; height: 100.0%;">Safari African Food, 1336 Blue Hill Avenue, Mattapan, MA 02126</div>`)[0];
            popup_b004fa3d072e4ff1a3cd6df0eaa025b5.setContent(html_42e2bba621d94003b868750035fedf9f);
        

        marker_6ca40d98d351461381f0e84de3ab3f48.bindPopup(popup_b004fa3d072e4ff1a3cd6df0eaa025b5)
        ;

        
    
    
            var marker_48617cf0350c485cab3af493eca7df16 = L.marker(
                [42.280662409839394, -71.08316080171028],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_7761133b07534934a91df734da5e5766 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_48617cf0350c485cab3af493eca7df16.setIcon(icon_7761133b07534934a91df734da5e5766);
        
    
        var popup_1305688434e34356aeb00bcaa65b231b = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_b321cd7602ff435c9a22e9280cef7698 = $(`<div id="html_b321cd7602ff435c9a22e9280cef7698" style="width: 100.0%; height: 100.0%;">Prestige Cuisine LLC, 924 Morton St, Boston, MA 02126</div>`)[0];
            popup_1305688434e34356aeb00bcaa65b231b.setContent(html_b321cd7602ff435c9a22e9280cef7698);
        

        marker_48617cf0350c485cab3af493eca7df16.bindPopup(popup_1305688434e34356aeb00bcaa65b231b)
        ;

        
    
    
            var marker_6cbeb9df2dc9469b95e433d591898337 = L.marker(
                [42.278585, -71.079822],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_beafdae13d3a463c8cdde471fd9a45cc = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_6cbeb9df2dc9469b95e433d591898337.setIcon(icon_beafdae13d3a463c8cdde471fd9a45cc);
        
    
        var popup_97e143d843464ce796cce84d1301f25e = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_c14205d727114175839a7e39ac631048 = $(`<div id="html_c14205d727114175839a7e39ac631048" style="width: 100.0%; height: 100.0%;">Pit Stop Barbecue, 888 Morton St A, Mattapan, MA 02126</div>`)[0];
            popup_97e143d843464ce796cce84d1301f25e.setContent(html_c14205d727114175839a7e39ac631048);
        

        marker_6cbeb9df2dc9469b95e433d591898337.bindPopup(popup_97e143d843464ce796cce84d1301f25e)
        ;

        
    
    
            var marker_e60ede67ef0e4ec2b662912deb314e83 = L.marker(
                [42.271709900000005, -71.09540780532785],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_bf427fe7a52947619cbe229063a0cde8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_e60ede67ef0e4ec2b662912deb314e83.setIcon(icon_bf427fe7a52947619cbe229063a0cde8);
        
    
        var popup_7ea261fbf5df4a21b906b32e70954127 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_1d4fcb0c9d064155b8f20462d7108143 = $(`<div id="html_1d4fcb0c9d064155b8f20462d7108143" style="width: 100.0%; height: 100.0%;">Ali&#39;s Roti Restaurant, 1188 Blue Hill Avenue, Mattapan, MA 02126</div>`)[0];
            popup_7ea261fbf5df4a21b906b32e70954127.setContent(html_1d4fcb0c9d064155b8f20462d7108143);
        

        marker_e60ede67ef0e4ec2b662912deb314e83.bindPopup(popup_7ea261fbf5df4a21b906b32e70954127)
        ;

        
    
    
            var marker_ae55aadec4fe4fe49fff71a83fb9010a = L.marker(
                [42.101584, -71.503715],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_71d92053770a4ed4b83a04fac6712a4f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_ae55aadec4fe4fe49fff71a83fb9010a.setIcon(icon_71d92053770a4ed4b83a04fac6712a4f);
        
    
        var popup_aafdfb0b95a34ad4a7a85825b2fef3a6 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_ed0b53b579374b1fb597cb382d4377cf = $(`<div id="html_ed0b53b579374b1fb597cb382d4377cf" style="width: 100.0%; height: 100.0%;">Larry Joe&#39;s New England FirePit, 30 Cape Rd, Mendon, MA 01756</div>`)[0];
            popup_aafdfb0b95a34ad4a7a85825b2fef3a6.setContent(html_ed0b53b579374b1fb597cb382d4377cf);
        

        marker_ae55aadec4fe4fe49fff71a83fb9010a.bindPopup(popup_aafdfb0b95a34ad4a7a85825b2fef3a6)
        ;

        
    
    
            var marker_68aae38da13041499ed713d1142f28cb = L.marker(
                [42.28152835, -71.23642385051701],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_d3a73fc4eecb410a9879fe8aa11470ea = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_68aae38da13041499ed713d1142f28cb.setIcon(icon_d3a73fc4eecb410a9879fe8aa11470ea);
        
    
        var popup_52884b9a47f14bec8ed889c4439095f7 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_6a8abebf40794989881aace6eb808854 = $(`<div id="html_6a8abebf40794989881aace6eb808854" style="width: 100.0%; height: 100.0%;">French Press Bakery &amp; Cafe, 74 Chapel St, Needham, MA 02492</div>`)[0];
            popup_52884b9a47f14bec8ed889c4439095f7.setContent(html_6a8abebf40794989881aace6eb808854);
        

        marker_68aae38da13041499ed713d1142f28cb.bindPopup(popup_52884b9a47f14bec8ed889c4439095f7)
        ;

        
    
    
            var marker_d96b79960a264598b072cb649eb100f6 = L.marker(
                [42.042460199999994, -70.839430795109],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_fb9429b0fc834b35be27723bc1ad3cf7 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_d96b79960a264598b072cb649eb100f6.setIcon(icon_fb9429b0fc834b35be27723bc1ad3cf7);
        
    
        var popup_ba4e54b59cab4201bb3b610d7024639c = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_613868483fe34e94a19a92147cd022f2 = $(`<div id="html_613868483fe34e94a19a92147cd022f2" style="width: 100.0%; height: 100.0%;">Gather, 35 School St, Pembroke, MA 02359</div>`)[0];
            popup_ba4e54b59cab4201bb3b610d7024639c.setContent(html_613868483fe34e94a19a92147cd022f2);
        

        marker_d96b79960a264598b072cb649eb100f6.bindPopup(popup_ba4e54b59cab4201bb3b610d7024639c)
        ;

        
    
    
            var marker_4b21cede713146aea01a68f6b4f5f4f2 = L.marker(
                [42.328464499999995, -71.0821485],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_10d964b2ec344915bcbac96f8c91999f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_4b21cede713146aea01a68f6b4f5f4f2.setIcon(icon_10d964b2ec344915bcbac96f8c91999f);
        
    
        var popup_1d9416f3f75b4e58907b230bbbde2dbd = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_6981cdd79fa14664ac62d16e74226ab0 = $(`<div id="html_6981cdd79fa14664ac62d16e74226ab0" style="width: 100.0%; height: 100.0%;">Suya Joint, 185 Dudley St, Boston, MA 02119</div>`)[0];
            popup_1d9416f3f75b4e58907b230bbbde2dbd.setContent(html_6981cdd79fa14664ac62d16e74226ab0);
        

        marker_4b21cede713146aea01a68f6b4f5f4f2.bindPopup(popup_1d9416f3f75b4e58907b230bbbde2dbd)
        ;

        
    
    
            var marker_712a8d1c586f4501ac469b122fca02ad = L.marker(
                [46.3144754, 11.0480288],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_2bdefbf58e554f9d8cbce7cd60555fde = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_712a8d1c586f4501ac469b122fca02ad.setIcon(icon_2bdefbf58e554f9d8cbce7cd60555fde);
        
    
        var popup_f985bb22b771479cb8586a4877d4796d = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_0d8f51872a574791a1ee3eb6dfc39e68 = $(`<div id="html_0d8f51872a574791a1ee3eb6dfc39e68" style="width: 100.0%; height: 100.0%;">Bintimani Restaurant, nan</div>`)[0];
            popup_f985bb22b771479cb8586a4877d4796d.setContent(html_0d8f51872a574791a1ee3eb6dfc39e68);
        

        marker_712a8d1c586f4501ac469b122fca02ad.bindPopup(popup_f985bb22b771479cb8586a4877d4796d)
        ;

        
    
    
            var marker_8d1771f3960641f192620dfbf70c2b26 = L.marker(
                [42.3916828, -71.09225049221519],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_2c00196e8b4f405ea98b3fcb4a27cca1 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_8d1771f3960641f192620dfbf70c2b26.setIcon(icon_2c00196e8b4f405ea98b3fcb4a27cca1);
        
    
        var popup_df97dcd1e37049e3a6757de2105f46f4 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_f35801941ab947948d57c905d7843f97 = $(`<div id="html_f35801941ab947948d57c905d7843f97" style="width: 100.0%; height: 100.0%;">Pikliz International Kitchen, 288 Broadway, Somerville, MA 02145</div>`)[0];
            popup_df97dcd1e37049e3a6757de2105f46f4.setContent(html_f35801941ab947948d57c905d7843f97);
        

        marker_8d1771f3960641f192620dfbf70c2b26.bindPopup(popup_df97dcd1e37049e3a6757de2105f46f4)
        ;

        
    
    
            var marker_cfe3b7e508c7493bb1769a07f7feda7b = L.marker(
                [42.393662104166665, -71.08344629166666],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_744d417952a4412c820a5600e7515141 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_cfe3b7e508c7493bb1769a07f7feda7b.setIcon(icon_744d417952a4412c820a5600e7515141);
        
    
        var popup_e40f58ea1e1f4afa9e0b8e285280fea1 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_44bd797a22164230847a69ec2c103450 = $(`<div id="html_44bd797a22164230847a69ec2c103450" style="width: 100.0%; height: 100.0%;">Sunrise Caribbean Cuisine, 76 Middlesex Ave, Somerville, MA 02145</div>`)[0];
            popup_e40f58ea1e1f4afa9e0b8e285280fea1.setContent(html_44bd797a22164230847a69ec2c103450);
        

        marker_cfe3b7e508c7493bb1769a07f7feda7b.bindPopup(popup_e40f58ea1e1f4afa9e0b8e285280fea1)
        ;

        
    
    
            var marker_54403b1c472b41918df11343f64323de = L.marker(
                [42.383897649999994, -71.10872930667514],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_b846b0abb7b341febac392a8b6b74028 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_54403b1c472b41918df11343f64323de.setIcon(icon_b846b0abb7b341febac392a8b6b74028);
        
    
        var popup_b6bd09afa6c8479fabbfe0a58d3002b5 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_b726283c782c44199d7e57a072bd0068 = $(`<div id="html_b726283c782c44199d7e57a072bd0068" style="width: 100.0%; height: 100.0%;">Morroccan Hospitality, 585 Somerville Ave, Somerville, MA 02143</div>`)[0];
            popup_b6bd09afa6c8479fabbfe0a58d3002b5.setContent(html_b726283c782c44199d7e57a072bd0068);
        

        marker_54403b1c472b41918df11343f64323de.bindPopup(popup_b6bd09afa6c8479fabbfe0a58d3002b5)
        ;

        
    
    
            var marker_342140a11a394ca3996aa405db713433 = L.marker(
                [42.38935444988811, -71.08704529854712],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_7dd6bd7b80bc4f01a49c261551d1839f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_342140a11a394ca3996aa405db713433.setIcon(icon_7dd6bd7b80bc4f01a49c261551d1839f);
        
    
        var popup_97902ce9986741df970de6f2361c3305 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_06866c8f44da4e2ca78156cb228f0c9a = $(`<div id="html_06866c8f44da4e2ca78156cb228f0c9a" style="width: 100.0%; height: 100.0%;">Fasika Ethiopian Restaurant, 145 Broadway, Somerville, MA 02145</div>`)[0];
            popup_97902ce9986741df970de6f2361c3305.setContent(html_06866c8f44da4e2ca78156cb228f0c9a);
        

        marker_342140a11a394ca3996aa405db713433.bindPopup(popup_97902ce9986741df970de6f2361c3305)
        ;

        
    
    
            var marker_2b5064e384334fb9ac6279b044a0ae06 = L.marker(
                [42.34190142268061, -71.0726427687514],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_2e17ae10662947b995c8a69d296dbf65 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_2b5064e384334fb9ac6279b044a0ae06.setIcon(icon_2e17ae10662947b995c8a69d296dbf65);
        
    
        var popup_8c30162640df4b738e0bbf32d1b61914 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_4f04dcace05f4435b76dd06fdd94666b = $(`<div id="html_4f04dcace05f4435b76dd06fdd94666b" style="width: 100.0%; height: 100.0%;">Vejigantes Restaurant, 57 W Dedham St, Boston, MA 02118</div>`)[0];
            popup_8c30162640df4b738e0bbf32d1b61914.setContent(html_4f04dcace05f4435b76dd06fdd94666b);
        

        marker_2b5064e384334fb9ac6279b044a0ae06.bindPopup(popup_8c30162640df4b738e0bbf32d1b61914)
        ;

        
    
    
            var marker_8bb8007a689e48988a74a7fa12c472eb = L.marker(
                [46.3144754, 11.0480288],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_c01e22ff030f4425aea0024078bb1daa = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_8bb8007a689e48988a74a7fa12c472eb.setIcon(icon_c01e22ff030f4425aea0024078bb1daa);
        
    
        var popup_530b6407051643e88aeee228edf232ee = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_ebea1b13f6bd4c1ea10730f08628918a = $(`<div id="html_ebea1b13f6bd4c1ea10730f08628918a" style="width: 100.0%; height: 100.0%;">White Lion Brewery , nan</div>`)[0];
            popup_530b6407051643e88aeee228edf232ee.setContent(html_ebea1b13f6bd4c1ea10730f08628918a);
        

        marker_8bb8007a689e48988a74a7fa12c472eb.bindPopup(popup_530b6407051643e88aeee228edf232ee)
        ;

        
    
    
            var marker_77b2ebd5371c4554b1abc46ae4026868 = L.marker(
                [42.272472, -71.789513],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_36da1ac3daee437eb378b0a163418458 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_77b2ebd5371c4554b1abc46ae4026868.setIcon(icon_36da1ac3daee437eb378b0a163418458);
        
    
        var popup_8149f3f7e0ea4d6e9e463d27179ecbdc = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_0b434ab556fc4c43b6f91d6563db74c9 = $(`<div id="html_0b434ab556fc4c43b6f91d6563db74c9" style="width: 100.0%; height: 100.0%;">Belmont Vegetarian, 157 Belmont St, Worcester, MA 01605</div>`)[0];
            popup_8149f3f7e0ea4d6e9e463d27179ecbdc.setContent(html_0b434ab556fc4c43b6f91d6563db74c9);
        

        marker_77b2ebd5371c4554b1abc46ae4026868.bindPopup(popup_8149f3f7e0ea4d6e9e463d27179ecbdc)
        ;

        
    
    
            var marker_ea1c205bd829420391a4d4cf6f4a9257 = L.marker(
                [46.3144754, 11.0480288],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_e09c4fe47127424aad1ce829dfe4a5b6 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_ea1c205bd829420391a4d4cf6f4a9257.setIcon(icon_e09c4fe47127424aad1ce829dfe4a5b6);
        
    
        var popup_e8b0312bedd54f96a5e1f7efde2163ce = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_d25aec457ae5473ca2e36fa27255324a = $(`<div id="html_d25aec457ae5473ca2e36fa27255324a" style="width: 100.0%; height: 100.0%;">Fatima&#39;s Cafe, nan</div>`)[0];
            popup_e8b0312bedd54f96a5e1f7efde2163ce.setContent(html_d25aec457ae5473ca2e36fa27255324a);
        

        marker_ea1c205bd829420391a4d4cf6f4a9257.bindPopup(popup_e8b0312bedd54f96a5e1f7efde2163ce)
        ;

        
    
    
            var marker_c2ce6760a2074d9e9a1287c2d721f8be = L.marker(
                [42.23840575, -71.79798449117754],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_2a7ff615c59d4190ab878185741e9644 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_c2ce6760a2074d9e9a1287c2d721f8be.setIcon(icon_2a7ff615c59d4190ab878185741e9644);
        
    
        var popup_fe0526f1da544b45aa77ff88abe3c8ea = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_89ef892cd85040f788b35d317e8cb601 = $(`<div id="html_89ef892cd85040f788b35d317e8cb601" style="width: 100.0%; height: 100.0%;">Anokye Krom, 687 Millbury St, Worcester, MA 01607</div>`)[0];
            popup_fe0526f1da544b45aa77ff88abe3c8ea.setContent(html_89ef892cd85040f788b35d317e8cb601);
        

        marker_c2ce6760a2074d9e9a1287c2d721f8be.bindPopup(popup_fe0526f1da544b45aa77ff88abe3c8ea)
        ;

        
    
    
            var marker_953039a47220475799c26e4df68dfe4b = L.marker(
                [42.28889652854537, -71.07127284208927],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_cce650a6508c4ed0a9b9d350f2727731 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "cutlery", "iconColor": "white", "iconSize": [27, 27], "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_953039a47220475799c26e4df68dfe4b.setIcon(icon_cce650a6508c4ed0a9b9d350f2727731);
        
    
        var popup_b8346ba17ede433c907dfcf7a51c1a0c = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_5f408299b0ba46159f4f5fb5876e24f9 = $(`<div id="html_5f408299b0ba46159f4f5fb5876e24f9" style="width: 100.0%; height: 100.0%;">Next Step Soul Food Café, 657 Washington St, Boston, MA 02124</div>`)[0];
            popup_b8346ba17ede433c907dfcf7a51c1a0c.setContent(html_5f408299b0ba46159f4f5fb5876e24f9);
        

        marker_953039a47220475799c26e4df68dfe4b.bindPopup(popup_b8346ba17ede433c907dfcf7a51c1a0c)
        ;

        
    
    
            var marker_f8e8a2a107994bbe84a92b7ef48315bc = L.marker(
                [42.42445746064315, -71.18353256501587],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_52db7db422c742ad854b687a2ceb2ee9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_f8e8a2a107994bbe84a92b7ef48315bc.setIcon(icon_52db7db422c742ad854b687a2ceb2ee9);
        
    
        var popup_1ceeeeaa93ea4bc7816892b2a27bedbf = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_40d7079ae9c8439f9ae601167a4a3fcc = $(`<div id="html_40d7079ae9c8439f9ae601167a4a3fcc" style="width: 100.0%; height: 100.0%;">RepHAIRations, 1339 Massachusetts Avenue Arlington, MA    02476</div>`)[0];
            popup_1ceeeeaa93ea4bc7816892b2a27bedbf.setContent(html_40d7079ae9c8439f9ae601167a4a3fcc);
        

        marker_f8e8a2a107994bbe84a92b7ef48315bc.bindPopup(popup_1ceeeeaa93ea4bc7816892b2a27bedbf)
        ;

        
    
    
            var marker_4528ac3911224ae5bfec5581441f165e = L.marker(
                [42.4222626, -71.1731739],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_8e76dceb1b004ffdb33360b707773116 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_4528ac3911224ae5bfec5581441f165e.setIcon(icon_8e76dceb1b004ffdb33360b707773116);
        
    
        var popup_2c4de496cd9d47ccb9c291d97fbf9679 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_8b1e029acf474a65ae1d308a9dc30395 = $(`<div id="html_8b1e029acf474a65ae1d308a9dc30395" style="width: 100.0%; height: 100.0%;">Mamadou&#39; Artisan Bakery, 677 Massachusetts Ave Arlington, MA 02476 Arlington Center</div>`)[0];
            popup_2c4de496cd9d47ccb9c291d97fbf9679.setContent(html_8b1e029acf474a65ae1d308a9dc30395);
        

        marker_4528ac3911224ae5bfec5581441f165e.bindPopup(popup_2c4de496cd9d47ccb9c291d97fbf9679)
        ;

        
    
    
            var marker_cf44b0d925b64a279b08bcfe7914888f = L.marker(
                [42.357021228571426, -71.05982048571428],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_c8c91a598aa6438096f383c382a146cc = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_cf44b0d925b64a279b08bcfe7914888f.setIcon(icon_c8c91a598aa6438096f383c382a146cc);
        
    
        var popup_bcad8acd86a6499983a599e07faeb8af = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_7dbcf2605e50422297e7e496fae0fa61 = $(`<div id="html_7dbcf2605e50422297e7e496fae0fa61" style="width: 100.0%; height: 100.0%;">Bebe Mursalin, 32 Province Street, Boston, MA 02108</div>`)[0];
            popup_bcad8acd86a6499983a599e07faeb8af.setContent(html_7dbcf2605e50422297e7e496fae0fa61);
        

        marker_cf44b0d925b64a279b08bcfe7914888f.bindPopup(popup_bcad8acd86a6499983a599e07faeb8af)
        ;

        
    
    
            var marker_e16ba452b71742aa9e95b88ccc775647 = L.marker(
                [42.356437, -71.05923179999999],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_5c06ba24611445699130da9db7b837a6 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_e16ba452b71742aa9e95b88ccc775647.setIcon(icon_5c06ba24611445699130da9db7b837a6);
        
    
        var popup_40132d220ffa487295ddc59901dd3f84 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_4066be1f4c7147c1acf971167f1e844c = $(`<div id="html_4066be1f4c7147c1acf971167f1e844c" style="width: 100.0%; height: 100.0%;">Boston Beauty Bar, 388 Washington St, Boston, MA 02108</div>`)[0];
            popup_40132d220ffa487295ddc59901dd3f84.setContent(html_4066be1f4c7147c1acf971167f1e844c);
        

        marker_e16ba452b71742aa9e95b88ccc775647.bindPopup(popup_40132d220ffa487295ddc59901dd3f84)
        ;

        
    
    
            var marker_d54cd8f8322b435e80fe219ea35f03d8 = L.marker(
                [42.3514905, -71.0729046],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_8023e131991b4c74806a67be5f900878 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_d54cd8f8322b435e80fe219ea35f03d8.setIcon(icon_8023e131991b4c74806a67be5f900878);
        
    
        var popup_7aee59f224984215b3c09b473ed1a0ce = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_fa41bb14950449fd988a72aed17ec775 = $(`<div id="html_fa41bb14950449fd988a72aed17ec775" style="width: 100.0%; height: 100.0%;">Hair Sessions , 437 Boylston St, Boston, MA 02116</div>`)[0];
            popup_7aee59f224984215b3c09b473ed1a0ce.setContent(html_fa41bb14950449fd988a72aed17ec775);
        

        marker_d54cd8f8322b435e80fe219ea35f03d8.bindPopup(popup_7aee59f224984215b3c09b473ed1a0ce)
        ;

        
    
    
            var marker_5ca5b73e66884756a49083152ccb7d01 = L.marker(
                [42.33476545836163, -71.12317553945721],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_be0ba07034554001a2d41506711991c8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_5ca5b73e66884756a49083152ccb7d01.setIcon(icon_be0ba07034554001a2d41506711991c8);
        
    
        var popup_193f33009076488498624502a8fc4b74 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_3322e5d8193d4ac4ba03cde05d23a8dc = $(`<div id="html_3322e5d8193d4ac4ba03cde05d23a8dc" style="width: 100.0%; height: 100.0%;">L&#39;Accent Women&#39;s Fashion, 395 A Washington Street, Brookline, MA 02446</div>`)[0];
            popup_193f33009076488498624502a8fc4b74.setContent(html_3322e5d8193d4ac4ba03cde05d23a8dc);
        

        marker_5ca5b73e66884756a49083152ccb7d01.bindPopup(popup_193f33009076488498624502a8fc4b74)
        ;

        
    
    
            var marker_444efddd63194609ab6a19e6d0175c8c = L.marker(
                [42.3729024, -71.1206388],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_b2989bda79614a849c396a86dca15c23 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_444efddd63194609ab6a19e6d0175c8c.setIcon(icon_b2989bda79614a849c396a86dca15c23);
        
    
        var popup_d7cc1c93207b46e1ab1ad729fc3868ee = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_835c54de8d9d46a6a8e26a13c218bfcb = $(`<div id="html_835c54de8d9d46a6a8e26a13c218bfcb" style="width: 100.0%; height: 100.0%;">Million Year Picnic (Comic Books), 99 Mount Auburn St, Cambridge, MA 02138</div>`)[0];
            popup_d7cc1c93207b46e1ab1ad729fc3868ee.setContent(html_835c54de8d9d46a6a8e26a13c218bfcb);
        

        marker_444efddd63194609ab6a19e6d0175c8c.bindPopup(popup_d7cc1c93207b46e1ab1ad729fc3868ee)
        ;

        
    
    
            var marker_18635b2c623b415592a92b05a3afa6b4 = L.marker(
                [42.36543733673469, -71.10395584693877],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_fd377af7a1cb4bd1a9655d4afd74700d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_18635b2c623b415592a92b05a3afa6b4.setIcon(icon_fd377af7a1cb4bd1a9655d4afd74700d);
        
    
        var popup_e3f6e57e5cd54524982059f5d09f8a9f = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_1a996f0be36d485ea630803c3ec32590 = $(`<div id="html_1a996f0be36d485ea630803c3ec32590" style="width: 100.0%; height: 100.0%;">Nu Image Barbershop, 98 River Street Cambridge, MA 02139</div>`)[0];
            popup_e3f6e57e5cd54524982059f5d09f8a9f.setContent(html_1a996f0be36d485ea630803c3ec32590);
        

        marker_18635b2c623b415592a92b05a3afa6b4.bindPopup(popup_e3f6e57e5cd54524982059f5d09f8a9f)
        ;

        
    
    
            var marker_9a83525810e04ad1b2e1ff3fbc551fbf = L.marker(
                [42.37825357142857, -71.06802628571428],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_154943572a1442c9aab7f434d506d06e = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_9a83525810e04ad1b2e1ff3fbc551fbf.setIcon(icon_154943572a1442c9aab7f434d506d06e);
        
    
        var popup_2b386529273842deb2b8af68c90b2b78 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_7cf0b408e0dd4962be7b3ccc41bec29a = $(`<div id="html_7cf0b408e0dd4962be7b3ccc41bec29a" style="width: 100.0%; height: 100.0%;">La Chic Dog Grooming Salon, 316 Main St, Charlestown, MA 02129</div>`)[0];
            popup_2b386529273842deb2b8af68c90b2b78.setContent(html_7cf0b408e0dd4962be7b3ccc41bec29a);
        

        marker_9a83525810e04ad1b2e1ff3fbc551fbf.bindPopup(popup_2b386529273842deb2b8af68c90b2b78)
        ;

        
    
    
            var marker_e260c002494a49899efba9b35d16bc02 = L.marker(
                [42.3094644, -71.1043642],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_a6c863ebda864362a1e34bf71287e408 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_e260c002494a49899efba9b35d16bc02.setIcon(icon_a6c863ebda864362a1e34bf71287e408);
        
    
        var popup_860f34e878bb46279c039846c3468229 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_54070eecbec54ff99dff1aedd0d2e1ab = $(`<div id="html_54070eecbec54ff99dff1aedd0d2e1ab" style="width: 100.0%; height: 100.0%;">Exodus Bagels, 3346 Washington St, Boston, MA 02130</div>`)[0];
            popup_860f34e878bb46279c039846c3468229.setContent(html_54070eecbec54ff99dff1aedd0d2e1ab);
        

        marker_e260c002494a49899efba9b35d16bc02.bindPopup(popup_860f34e878bb46279c039846c3468229)
        ;

        
    
    
            var marker_1ae1e75837d44f589948a6575e9a006a = L.marker(
                [42.328802448947414, -71.0835718966415],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_2f02a19fbcaf48549c3644e24817cdc8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_1ae1e75837d44f589948a6575e9a006a.setIcon(icon_2f02a19fbcaf48549c3644e24817cdc8);
        
    
        var popup_a6bb9d4436de4e0b9f9b113fac64a38a = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_2277eb4156c94befb86d3d579933f3dc = $(`<div id="html_2277eb4156c94befb86d3d579933f3dc" style="width: 100.0%; height: 100.0%;">Frugal Bookstore, 57 Warren St, Roxbury, MA 02119</div>`)[0];
            popup_a6bb9d4436de4e0b9f9b113fac64a38a.setContent(html_2277eb4156c94befb86d3d579933f3dc);
        

        marker_1ae1e75837d44f589948a6575e9a006a.bindPopup(popup_a6bb9d4436de4e0b9f9b113fac64a38a)
        ;

        
    
    
            var marker_d5822a2b6b6b4197992099ebf8be2c08 = L.marker(
                [42.3896982, -71.0879773],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_3d38e263de184e6ab0ce144852de2525 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_d5822a2b6b6b4197992099ebf8be2c08.setIcon(icon_3d38e263de184e6ab0ce144852de2525);
        
    
        var popup_aed09034062d4674927e943985244ec0 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_5a4feed29ca549498f42c8b2f071f8cc = $(`<div id="html_5a4feed29ca549498f42c8b2f071f8cc" style="width: 100.0%; height: 100.0%;">Villeside CUstoms , 491 Broadway, Somerville, MA 02145</div>`)[0];
            popup_aed09034062d4674927e943985244ec0.setContent(html_5a4feed29ca549498f42c8b2f071f8cc);
        

        marker_d5822a2b6b6b4197992099ebf8be2c08.bindPopup(popup_aed09034062d4674927e943985244ec0)
        ;

        
    
    
            var marker_6492ed76ebb24ca0a0f337a798b8dbfc = L.marker(
                [42.38580415, -71.07797437393333],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_9698c877a5034fb9bce6f9a1321120d3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_6492ed76ebb24ca0a0f337a798b8dbfc.setIcon(icon_9698c877a5034fb9bce6f9a1321120d3);
        
    
        var popup_40ec21eb912d48229284eb3db3f0e4f6 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_dde47b6582764356b64c64d35eac4e1d = $(`<div id="html_dde47b6582764356b64c64d35eac4e1d" style="width: 100.0%; height: 100.0%;">Fadil African Hair Braiding, 8 Broadway, Somerville, MA 02145</div>`)[0];
            popup_40ec21eb912d48229284eb3db3f0e4f6.setContent(html_dde47b6582764356b64c64d35eac4e1d);
        

        marker_6492ed76ebb24ca0a0f337a798b8dbfc.bindPopup(popup_40ec21eb912d48229284eb3db3f0e4f6)
        ;

        
    
    
            var marker_245f0af147f046d782c589367c24a14e = L.marker(
                [42.4008434, -71.1172454],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_d402cb7b52cf48578208e0e639f34a74 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_245f0af147f046d782c589367c24a14e.setIcon(icon_d402cb7b52cf48578208e0e639f34a74);
        
    
        var popup_585d29e43ff74b1388316a63b57fdcb4 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_c474a52dd3f0462da05d3a1a1f01831e = $(`<div id="html_c474a52dd3f0462da05d3a1a1f01831e" style="width: 100.0%; height: 100.0%;">Just the Way You Like It Barber Shop, 1299 Broadway, Somerville, MA 02144</div>`)[0];
            popup_585d29e43ff74b1388316a63b57fdcb4.setContent(html_c474a52dd3f0462da05d3a1a1f01831e);
        

        marker_245f0af147f046d782c589367c24a14e.bindPopup(popup_585d29e43ff74b1388316a63b57fdcb4)
        ;

        
    
    
            var marker_d334431db8d046119a516ac125f4db77 = L.marker(
                [42.310416621645516, -71.08934653172189],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_ab84d98d5fb0480d8f568036f05ad062 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "shopping bag", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_d334431db8d046119a516ac125f4db77.setIcon(icon_ab84d98d5fb0480d8f568036f05ad062);
        
    
        var popup_7cf677839fda454b992746645a1cc3ee = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_c4e97dd57298455ab2451807c8c462ed = $(`<div id="html_c4e97dd57298455ab2451807c8c462ed" style="width: 100.0%; height: 100.0%;">The G| Code House,  43 Hutchings Street in Roxbury, MA </div>`)[0];
            popup_7cf677839fda454b992746645a1cc3ee.setContent(html_c4e97dd57298455ab2451807c8c462ed);
        

        marker_d334431db8d046119a516ac125f4db77.bindPopup(popup_7cf677839fda454b992746645a1cc3ee)
        ;

        
    
    
            var marker_716cb2a2014842b391e56f89eb23b964 = L.marker(
                [42.42445746064315, -71.18353256501587],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_e01beedf77594e609df19a8a9c4fe645 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_716cb2a2014842b391e56f89eb23b964.setIcon(icon_e01beedf77594e609df19a8a9c4fe645);
        
    
        var popup_dde1a432be7b4655b00561be54058fe2 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_2d57e590a76843e8b759de2781228717 = $(`<div id="html_2d57e590a76843e8b759de2781228717" style="width: 100.0%; height: 100.0%;">RepHAIRations, 1339 Massachusetts Avenue Arlington, MA    02476</div>`)[0];
            popup_dde1a432be7b4655b00561be54058fe2.setContent(html_2d57e590a76843e8b759de2781228717);
        

        marker_716cb2a2014842b391e56f89eb23b964.bindPopup(popup_dde1a432be7b4655b00561be54058fe2)
        ;

        
    
    
            var marker_2e93c0fd13bf41dfa9c49cd7a06b3e4c = L.marker(
                [42.4222626, -71.1731739],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_c692cce1e9194c93b456935521967657 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_2e93c0fd13bf41dfa9c49cd7a06b3e4c.setIcon(icon_c692cce1e9194c93b456935521967657);
        
    
        var popup_011efc6edde64720843fb42878f778ca = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_99f4ba1c928f4559b62a2db4126e97a7 = $(`<div id="html_99f4ba1c928f4559b62a2db4126e97a7" style="width: 100.0%; height: 100.0%;">Mamadou&#39; Artisan Bakery, 677 Massachusetts Ave Arlington, MA 02476 Arlington Center</div>`)[0];
            popup_011efc6edde64720843fb42878f778ca.setContent(html_99f4ba1c928f4559b62a2db4126e97a7);
        

        marker_2e93c0fd13bf41dfa9c49cd7a06b3e4c.bindPopup(popup_011efc6edde64720843fb42878f778ca)
        ;

        
    
    
            var marker_bde9a7955fce45c9a74048d45d372b18 = L.marker(
                [42.357021228571426, -71.05982048571428],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_eec5e1fc0a5c452d8d4f1e2b22943587 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_bde9a7955fce45c9a74048d45d372b18.setIcon(icon_eec5e1fc0a5c452d8d4f1e2b22943587);
        
    
        var popup_4bd4c8fe7ba64e0ca2193f0bf322ebcd = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_f7f304827cad426d8c084bc8ce91faa4 = $(`<div id="html_f7f304827cad426d8c084bc8ce91faa4" style="width: 100.0%; height: 100.0%;">Bebe Mursalin, 32 Province Street, Boston, MA 02108</div>`)[0];
            popup_4bd4c8fe7ba64e0ca2193f0bf322ebcd.setContent(html_f7f304827cad426d8c084bc8ce91faa4);
        

        marker_bde9a7955fce45c9a74048d45d372b18.bindPopup(popup_4bd4c8fe7ba64e0ca2193f0bf322ebcd)
        ;

        
    
    
            var marker_39651c7ed40645969b97621797cd6c58 = L.marker(
                [42.356437, -71.05923179999999],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_41f9848cb36843d0bbe9bacb68536391 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_39651c7ed40645969b97621797cd6c58.setIcon(icon_41f9848cb36843d0bbe9bacb68536391);
        
    
        var popup_fb9060e716e04d9a8e21cdc9bae09282 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_3d596af661554d7daac56ecca98606dd = $(`<div id="html_3d596af661554d7daac56ecca98606dd" style="width: 100.0%; height: 100.0%;">Boston Beauty Bar, 388 Washington St, Boston, MA 02108</div>`)[0];
            popup_fb9060e716e04d9a8e21cdc9bae09282.setContent(html_3d596af661554d7daac56ecca98606dd);
        

        marker_39651c7ed40645969b97621797cd6c58.bindPopup(popup_fb9060e716e04d9a8e21cdc9bae09282)
        ;

        
    
    
            var marker_2b30a57a5e134636a695cb91877a63d4 = L.marker(
                [42.3514905, -71.0729046],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_db516344fafc449983ab0be6926a36cb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_2b30a57a5e134636a695cb91877a63d4.setIcon(icon_db516344fafc449983ab0be6926a36cb);
        
    
        var popup_64152020f2934d0a91e9505e8c24bf6f = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_d77fcb7867714d7883bc47831a7c8068 = $(`<div id="html_d77fcb7867714d7883bc47831a7c8068" style="width: 100.0%; height: 100.0%;">Hair Sessions , 437 Boylston St, Boston, MA 02116</div>`)[0];
            popup_64152020f2934d0a91e9505e8c24bf6f.setContent(html_d77fcb7867714d7883bc47831a7c8068);
        

        marker_2b30a57a5e134636a695cb91877a63d4.bindPopup(popup_64152020f2934d0a91e9505e8c24bf6f)
        ;

        
    
    
            var marker_65850ffa0d3b40d681c2e8be1ce09df8 = L.marker(
                [42.33476545836163, -71.12317553945721],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_fcbd16b26e3840339eb58812e6b91da6 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_65850ffa0d3b40d681c2e8be1ce09df8.setIcon(icon_fcbd16b26e3840339eb58812e6b91da6);
        
    
        var popup_26b406749e5b4f29bef5f19db72d2294 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_0398db8b3b204776a1ea976ec461d0bf = $(`<div id="html_0398db8b3b204776a1ea976ec461d0bf" style="width: 100.0%; height: 100.0%;">L&#39;Accent Women&#39;s Fashion, 395 A Washington Street, Brookline, MA 02446</div>`)[0];
            popup_26b406749e5b4f29bef5f19db72d2294.setContent(html_0398db8b3b204776a1ea976ec461d0bf);
        

        marker_65850ffa0d3b40d681c2e8be1ce09df8.bindPopup(popup_26b406749e5b4f29bef5f19db72d2294)
        ;

        
    
    
            var marker_a5e1c502ef0c4518816a258cd816789e = L.marker(
                [42.3729024, -71.1206388],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_3fad14a6f637429aba94220b26f2ab60 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_a5e1c502ef0c4518816a258cd816789e.setIcon(icon_3fad14a6f637429aba94220b26f2ab60);
        
    
        var popup_7cf0dd7092d8452d923007dc87100599 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_dd61406b17c44c0e89d7d0df9bb55901 = $(`<div id="html_dd61406b17c44c0e89d7d0df9bb55901" style="width: 100.0%; height: 100.0%;">Million Year Picnic (Comic Books), 99 Mount Auburn St, Cambridge, MA 02138</div>`)[0];
            popup_7cf0dd7092d8452d923007dc87100599.setContent(html_dd61406b17c44c0e89d7d0df9bb55901);
        

        marker_a5e1c502ef0c4518816a258cd816789e.bindPopup(popup_7cf0dd7092d8452d923007dc87100599)
        ;

        
    
    
            var marker_ecdd0fd9b6d3437a8b0a3fcaf83e1e7d = L.marker(
                [42.36543733673469, -71.10395584693877],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_cade8fa9f64a41ea92b2cdbff84c89c9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_ecdd0fd9b6d3437a8b0a3fcaf83e1e7d.setIcon(icon_cade8fa9f64a41ea92b2cdbff84c89c9);
        
    
        var popup_1a5b5a00627841b4a3693edadc609ec3 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_8ad6a278bf5142e299a16a81b60c4591 = $(`<div id="html_8ad6a278bf5142e299a16a81b60c4591" style="width: 100.0%; height: 100.0%;">Nu Image Barbershop, 98 River Street Cambridge, MA 02139</div>`)[0];
            popup_1a5b5a00627841b4a3693edadc609ec3.setContent(html_8ad6a278bf5142e299a16a81b60c4591);
        

        marker_ecdd0fd9b6d3437a8b0a3fcaf83e1e7d.bindPopup(popup_1a5b5a00627841b4a3693edadc609ec3)
        ;

        
    
    
            var marker_35ec484a7de44d6cadf667b63b0c6aa8 = L.marker(
                [42.37825357142857, -71.06802628571428],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_d49d5b444eff4285974211f85e3cc03d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_35ec484a7de44d6cadf667b63b0c6aa8.setIcon(icon_d49d5b444eff4285974211f85e3cc03d);
        
    
        var popup_526ee78fc50a4e51bb685576054cc96a = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_05fa41c2d05f495fb15d760f58296837 = $(`<div id="html_05fa41c2d05f495fb15d760f58296837" style="width: 100.0%; height: 100.0%;">La Chic Dog Grooming Salon, 316 Main St, Charlestown, MA 02129</div>`)[0];
            popup_526ee78fc50a4e51bb685576054cc96a.setContent(html_05fa41c2d05f495fb15d760f58296837);
        

        marker_35ec484a7de44d6cadf667b63b0c6aa8.bindPopup(popup_526ee78fc50a4e51bb685576054cc96a)
        ;

        
    
    
            var marker_e30e24682bf6446abb2917e3504fa07d = L.marker(
                [42.3094644, -71.1043642],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_23708b505aa7454baaef5b052ebe18bf = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_e30e24682bf6446abb2917e3504fa07d.setIcon(icon_23708b505aa7454baaef5b052ebe18bf);
        
    
        var popup_02a18028ede54fa5af827d0b7b2feb29 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_10b98f1e242145a3b726bac792d5e2e0 = $(`<div id="html_10b98f1e242145a3b726bac792d5e2e0" style="width: 100.0%; height: 100.0%;">Exodus Bagels, 3346 Washington St, Boston, MA 02130</div>`)[0];
            popup_02a18028ede54fa5af827d0b7b2feb29.setContent(html_10b98f1e242145a3b726bac792d5e2e0);
        

        marker_e30e24682bf6446abb2917e3504fa07d.bindPopup(popup_02a18028ede54fa5af827d0b7b2feb29)
        ;

        
    
    
            var marker_239c0dde8c25411caa4e2dd885c6f67d = L.marker(
                [42.328802448947414, -71.0835718966415],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_a2d44a2592554f24ac6ab811b0f5c517 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_239c0dde8c25411caa4e2dd885c6f67d.setIcon(icon_a2d44a2592554f24ac6ab811b0f5c517);
        
    
        var popup_48066c29cb2e4395a2536c841ac24aa2 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_9c267d7be6a5448fa0518bb480dda22a = $(`<div id="html_9c267d7be6a5448fa0518bb480dda22a" style="width: 100.0%; height: 100.0%;">Frugal Bookstore, 57 Warren St, Roxbury, MA 02119</div>`)[0];
            popup_48066c29cb2e4395a2536c841ac24aa2.setContent(html_9c267d7be6a5448fa0518bb480dda22a);
        

        marker_239c0dde8c25411caa4e2dd885c6f67d.bindPopup(popup_48066c29cb2e4395a2536c841ac24aa2)
        ;

        
    
    
            var marker_b08696954bd242618b778145b1657a16 = L.marker(
                [42.3896982, -71.0879773],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_19aac5cc4172423d83d0e61edafc24dd = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_b08696954bd242618b778145b1657a16.setIcon(icon_19aac5cc4172423d83d0e61edafc24dd);
        
    
        var popup_f3b19240a5354f688b4aab92ab495a63 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_b472b8e6107e44d983c9d3f4bdbd772e = $(`<div id="html_b472b8e6107e44d983c9d3f4bdbd772e" style="width: 100.0%; height: 100.0%;">Villeside CUstoms , 491 Broadway, Somerville, MA 02145</div>`)[0];
            popup_f3b19240a5354f688b4aab92ab495a63.setContent(html_b472b8e6107e44d983c9d3f4bdbd772e);
        

        marker_b08696954bd242618b778145b1657a16.bindPopup(popup_f3b19240a5354f688b4aab92ab495a63)
        ;

        
    
    
            var marker_bce74437426246e7b8e801b486ff0378 = L.marker(
                [42.38580415, -71.07797437393333],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_297fd7936b5f4f5da6b598afb4e894ee = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_bce74437426246e7b8e801b486ff0378.setIcon(icon_297fd7936b5f4f5da6b598afb4e894ee);
        
    
        var popup_a35c4882dbe94f28a581874feabe2fa4 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_38280373050646b6b22796870dcbcc04 = $(`<div id="html_38280373050646b6b22796870dcbcc04" style="width: 100.0%; height: 100.0%;">Fadil African Hair Braiding, 8 Broadway, Somerville, MA 02145</div>`)[0];
            popup_a35c4882dbe94f28a581874feabe2fa4.setContent(html_38280373050646b6b22796870dcbcc04);
        

        marker_bce74437426246e7b8e801b486ff0378.bindPopup(popup_a35c4882dbe94f28a581874feabe2fa4)
        ;

        
    
    
            var marker_66111dedc52d4af8b56a56bfe4c04746 = L.marker(
                [42.4008434, -71.1172454],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_1cbbd08307854d85a072ed068d7fb375 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_66111dedc52d4af8b56a56bfe4c04746.setIcon(icon_1cbbd08307854d85a072ed068d7fb375);
        
    
        var popup_36f23d5d49714c06aa94923f96a0f40f = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_cf178c9d71244a77b6c454b695645f1c = $(`<div id="html_cf178c9d71244a77b6c454b695645f1c" style="width: 100.0%; height: 100.0%;">Just the Way You Like It Barber Shop, 1299 Broadway, Somerville, MA 02144</div>`)[0];
            popup_36f23d5d49714c06aa94923f96a0f40f.setContent(html_cf178c9d71244a77b6c454b695645f1c);
        

        marker_66111dedc52d4af8b56a56bfe4c04746.bindPopup(popup_36f23d5d49714c06aa94923f96a0f40f)
        ;

        
    
    
            var marker_5754b212abb54e3f9ef1dae5c80cc22b = L.marker(
                [42.310416621645516, -71.08934653172189],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_c019d0902ba343c085a8569d1b86a396 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "building", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_5754b212abb54e3f9ef1dae5c80cc22b.setIcon(icon_c019d0902ba343c085a8569d1b86a396);
        
    
        var popup_907b7f0dafdf442f9c0c8ea58d1c7b84 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_fb5f904f80a6489293469106065e767c = $(`<div id="html_fb5f904f80a6489293469106065e767c" style="width: 100.0%; height: 100.0%;">The G| Code House,  43 Hutchings Street in Roxbury, MA </div>`)[0];
            popup_907b7f0dafdf442f9c0c8ea58d1c7b84.setContent(html_fb5f904f80a6489293469106065e767c);
        

        marker_5754b212abb54e3f9ef1dae5c80cc22b.bindPopup(popup_907b7f0dafdf442f9c0c8ea58d1c7b84)
        ;

        
    
    
            var marker_2d4ffeb5973142da90d64eb8ca48a169 = L.marker(
                [42.42445746064315, -71.18353256501587],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_4b5c507a651845afa945aa948d91fbe8 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_2d4ffeb5973142da90d64eb8ca48a169.setIcon(icon_4b5c507a651845afa945aa948d91fbe8);
        
    
        var popup_881643ca9b474470b6acd57d106bd743 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_bc28442c6ee54c3b89829c95401bf8b0 = $(`<div id="html_bc28442c6ee54c3b89829c95401bf8b0" style="width: 100.0%; height: 100.0%;">RepHAIRations, 1339 Massachusetts Avenue Arlington, MA    02476</div>`)[0];
            popup_881643ca9b474470b6acd57d106bd743.setContent(html_bc28442c6ee54c3b89829c95401bf8b0);
        

        marker_2d4ffeb5973142da90d64eb8ca48a169.bindPopup(popup_881643ca9b474470b6acd57d106bd743)
        ;

        
    
    
            var marker_9d65e9dd6bcb457eb8dc202d83faf919 = L.marker(
                [42.4222626, -71.1731739],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_07678706b1c74d649e61db535e281e4d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_9d65e9dd6bcb457eb8dc202d83faf919.setIcon(icon_07678706b1c74d649e61db535e281e4d);
        
    
        var popup_4f08040375f445e0baab573e2f946665 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_65ec7c8b29aa45fe8114b431d4f6fbf6 = $(`<div id="html_65ec7c8b29aa45fe8114b431d4f6fbf6" style="width: 100.0%; height: 100.0%;">Mamadou&#39; Artisan Bakery, 677 Massachusetts Ave Arlington, MA 02476 Arlington Center</div>`)[0];
            popup_4f08040375f445e0baab573e2f946665.setContent(html_65ec7c8b29aa45fe8114b431d4f6fbf6);
        

        marker_9d65e9dd6bcb457eb8dc202d83faf919.bindPopup(popup_4f08040375f445e0baab573e2f946665)
        ;

        
    
    
            var marker_5493769a430d429c9af5f3ff942a7ea3 = L.marker(
                [42.357021228571426, -71.05982048571428],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_e229c792b7a746c3af6de0b9c4c4badd = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_5493769a430d429c9af5f3ff942a7ea3.setIcon(icon_e229c792b7a746c3af6de0b9c4c4badd);
        
    
        var popup_8a0f341cd30442258f22e00524a1e3e4 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_5786fa3b8d684103b860e7e642b75fb3 = $(`<div id="html_5786fa3b8d684103b860e7e642b75fb3" style="width: 100.0%; height: 100.0%;">Bebe Mursalin, 32 Province Street, Boston, MA 02108</div>`)[0];
            popup_8a0f341cd30442258f22e00524a1e3e4.setContent(html_5786fa3b8d684103b860e7e642b75fb3);
        

        marker_5493769a430d429c9af5f3ff942a7ea3.bindPopup(popup_8a0f341cd30442258f22e00524a1e3e4)
        ;

        
    
    
            var marker_96dbbe8bb9674e80b419c8a33b532006 = L.marker(
                [42.356437, -71.05923179999999],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_b9f3805932674aa2b867e4f086cfd421 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_96dbbe8bb9674e80b419c8a33b532006.setIcon(icon_b9f3805932674aa2b867e4f086cfd421);
        
    
        var popup_cc317fd2c47944989f15b059b7f882cd = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_606db53825aa423e9b8dc9c6bc0d1629 = $(`<div id="html_606db53825aa423e9b8dc9c6bc0d1629" style="width: 100.0%; height: 100.0%;">Boston Beauty Bar, 388 Washington St, Boston, MA 02108</div>`)[0];
            popup_cc317fd2c47944989f15b059b7f882cd.setContent(html_606db53825aa423e9b8dc9c6bc0d1629);
        

        marker_96dbbe8bb9674e80b419c8a33b532006.bindPopup(popup_cc317fd2c47944989f15b059b7f882cd)
        ;

        
    
    
            var marker_6406a4f89087433badbda7344ff3cb1c = L.marker(
                [42.3514905, -71.0729046],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_b0d1984108f048209b1c833672983b1b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_6406a4f89087433badbda7344ff3cb1c.setIcon(icon_b0d1984108f048209b1c833672983b1b);
        
    
        var popup_04c1ccc8687c446db48c44c4f21d7833 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_8be35f2a7dbd43aa95c2bc3c13942a0a = $(`<div id="html_8be35f2a7dbd43aa95c2bc3c13942a0a" style="width: 100.0%; height: 100.0%;">Hair Sessions , 437 Boylston St, Boston, MA 02116</div>`)[0];
            popup_04c1ccc8687c446db48c44c4f21d7833.setContent(html_8be35f2a7dbd43aa95c2bc3c13942a0a);
        

        marker_6406a4f89087433badbda7344ff3cb1c.bindPopup(popup_04c1ccc8687c446db48c44c4f21d7833)
        ;

        
    
    
            var marker_ba1527731cd943f9b0c09eaf947e94e3 = L.marker(
                [42.33476545836163, -71.12317553945721],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_fef10f05853e40d3bb206352874d9fbb = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_ba1527731cd943f9b0c09eaf947e94e3.setIcon(icon_fef10f05853e40d3bb206352874d9fbb);
        
    
        var popup_6e0c029fca7a4b9bab5a816d3323085f = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_1b71433a194f458c90c7c798d6f8cde0 = $(`<div id="html_1b71433a194f458c90c7c798d6f8cde0" style="width: 100.0%; height: 100.0%;">L&#39;Accent Women&#39;s Fashion, 395 A Washington Street, Brookline, MA 02446</div>`)[0];
            popup_6e0c029fca7a4b9bab5a816d3323085f.setContent(html_1b71433a194f458c90c7c798d6f8cde0);
        

        marker_ba1527731cd943f9b0c09eaf947e94e3.bindPopup(popup_6e0c029fca7a4b9bab5a816d3323085f)
        ;

        
    
    
            var marker_5fc4cc22b6774b9da531d07328e0850a = L.marker(
                [42.3729024, -71.1206388],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_8e77b77cecc94a6cb049c4d999730d2a = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_5fc4cc22b6774b9da531d07328e0850a.setIcon(icon_8e77b77cecc94a6cb049c4d999730d2a);
        
    
        var popup_152d70ea6f6043a3a65c1db86dc66ec1 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_7e4d86881709407c95133ca35b65ac32 = $(`<div id="html_7e4d86881709407c95133ca35b65ac32" style="width: 100.0%; height: 100.0%;">Million Year Picnic (Comic Books), 99 Mount Auburn St, Cambridge, MA 02138</div>`)[0];
            popup_152d70ea6f6043a3a65c1db86dc66ec1.setContent(html_7e4d86881709407c95133ca35b65ac32);
        

        marker_5fc4cc22b6774b9da531d07328e0850a.bindPopup(popup_152d70ea6f6043a3a65c1db86dc66ec1)
        ;

        
    
    
            var marker_2968fc20cda74c7881ca242347212a45 = L.marker(
                [42.36543733673469, -71.10395584693877],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_0e2cfa3985f543f29be8c521ba7a3888 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_2968fc20cda74c7881ca242347212a45.setIcon(icon_0e2cfa3985f543f29be8c521ba7a3888);
        
    
        var popup_9a01ac9d59854295aa78569568a9ab5c = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_90591e4766fd474a9cb98caa3200f40c = $(`<div id="html_90591e4766fd474a9cb98caa3200f40c" style="width: 100.0%; height: 100.0%;">Nu Image Barbershop, 98 River Street Cambridge, MA 02139</div>`)[0];
            popup_9a01ac9d59854295aa78569568a9ab5c.setContent(html_90591e4766fd474a9cb98caa3200f40c);
        

        marker_2968fc20cda74c7881ca242347212a45.bindPopup(popup_9a01ac9d59854295aa78569568a9ab5c)
        ;

        
    
    
            var marker_6ddad955e1c14b44950364fed705f64f = L.marker(
                [42.37825357142857, -71.06802628571428],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_6c5a161fe5db4a66b6e36748306feee9 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_6ddad955e1c14b44950364fed705f64f.setIcon(icon_6c5a161fe5db4a66b6e36748306feee9);
        
    
        var popup_6e473c5dfe1a4b1989cbc19f85b9d984 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_95031957d2c64ffe96b600a80c150b25 = $(`<div id="html_95031957d2c64ffe96b600a80c150b25" style="width: 100.0%; height: 100.0%;">La Chic Dog Grooming Salon, 316 Main St, Charlestown, MA 02129</div>`)[0];
            popup_6e473c5dfe1a4b1989cbc19f85b9d984.setContent(html_95031957d2c64ffe96b600a80c150b25);
        

        marker_6ddad955e1c14b44950364fed705f64f.bindPopup(popup_6e473c5dfe1a4b1989cbc19f85b9d984)
        ;

        
    
    
            var marker_8e770c1e8b8143ab9d35571f9d4809ac = L.marker(
                [42.3094644, -71.1043642],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_54f76756c51c4d359c50c8716955573b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_8e770c1e8b8143ab9d35571f9d4809ac.setIcon(icon_54f76756c51c4d359c50c8716955573b);
        
    
        var popup_2fb23b5f63d74a5d961850a81ca6bf7f = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_0a2bbda263dc48a689414051bed5b459 = $(`<div id="html_0a2bbda263dc48a689414051bed5b459" style="width: 100.0%; height: 100.0%;">Exodus Bagels, 3346 Washington St, Boston, MA 02130</div>`)[0];
            popup_2fb23b5f63d74a5d961850a81ca6bf7f.setContent(html_0a2bbda263dc48a689414051bed5b459);
        

        marker_8e770c1e8b8143ab9d35571f9d4809ac.bindPopup(popup_2fb23b5f63d74a5d961850a81ca6bf7f)
        ;

        
    
    
            var marker_9b75038194f644d88ed55e393ad77049 = L.marker(
                [42.328802448947414, -71.0835718966415],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_c6575b359f0d4bea97895fd3b5967aba = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_9b75038194f644d88ed55e393ad77049.setIcon(icon_c6575b359f0d4bea97895fd3b5967aba);
        
    
        var popup_e9ca03186ad14cc89765d522cecbe31f = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_4abe6b4ae18642a8bd285dde49426dc2 = $(`<div id="html_4abe6b4ae18642a8bd285dde49426dc2" style="width: 100.0%; height: 100.0%;">Frugal Bookstore, 57 Warren St, Roxbury, MA 02119</div>`)[0];
            popup_e9ca03186ad14cc89765d522cecbe31f.setContent(html_4abe6b4ae18642a8bd285dde49426dc2);
        

        marker_9b75038194f644d88ed55e393ad77049.bindPopup(popup_e9ca03186ad14cc89765d522cecbe31f)
        ;

        
    
    
            var marker_4b9917dbf13a4a6cbad11a17081a650a = L.marker(
                [42.3896982, -71.0879773],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_c6b8e25a7cfb4ecb99b80a2baea6a376 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_4b9917dbf13a4a6cbad11a17081a650a.setIcon(icon_c6b8e25a7cfb4ecb99b80a2baea6a376);
        
    
        var popup_b0dff87ade5941a3882b3e06b847ec58 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_b51f21790c7f4244becdf5e01723bd68 = $(`<div id="html_b51f21790c7f4244becdf5e01723bd68" style="width: 100.0%; height: 100.0%;">Villeside CUstoms , 491 Broadway, Somerville, MA 02145</div>`)[0];
            popup_b0dff87ade5941a3882b3e06b847ec58.setContent(html_b51f21790c7f4244becdf5e01723bd68);
        

        marker_4b9917dbf13a4a6cbad11a17081a650a.bindPopup(popup_b0dff87ade5941a3882b3e06b847ec58)
        ;

        
    
    
            var marker_7e2ad4fe9acb441fa66ab10d9c630206 = L.marker(
                [42.38580415, -71.07797437393333],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_cc577a0b9652432b9e1d5fa072c161ef = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_7e2ad4fe9acb441fa66ab10d9c630206.setIcon(icon_cc577a0b9652432b9e1d5fa072c161ef);
        
    
        var popup_8d30df71126649b2976982085023f6cb = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_9bdb364a584045f8b7eb99c5adab4a5d = $(`<div id="html_9bdb364a584045f8b7eb99c5adab4a5d" style="width: 100.0%; height: 100.0%;">Fadil African Hair Braiding, 8 Broadway, Somerville, MA 02145</div>`)[0];
            popup_8d30df71126649b2976982085023f6cb.setContent(html_9bdb364a584045f8b7eb99c5adab4a5d);
        

        marker_7e2ad4fe9acb441fa66ab10d9c630206.bindPopup(popup_8d30df71126649b2976982085023f6cb)
        ;

        
    
    
            var marker_09aa35555ce645b3a2cc65f63ddee36f = L.marker(
                [42.4008434, -71.1172454],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_dfdfd60756a741aca8d788065f92fcec = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_09aa35555ce645b3a2cc65f63ddee36f.setIcon(icon_dfdfd60756a741aca8d788065f92fcec);
        
    
        var popup_eb6ece2f45a748a79c527313b96140fd = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_a0c13ceeaa6b4470a5802ff4b232abea = $(`<div id="html_a0c13ceeaa6b4470a5802ff4b232abea" style="width: 100.0%; height: 100.0%;">Just the Way You Like It Barber Shop, 1299 Broadway, Somerville, MA 02144</div>`)[0];
            popup_eb6ece2f45a748a79c527313b96140fd.setContent(html_a0c13ceeaa6b4470a5802ff4b232abea);
        

        marker_09aa35555ce645b3a2cc65f63ddee36f.bindPopup(popup_eb6ece2f45a748a79c527313b96140fd)
        ;

        
    
    
            var marker_99eef5908f4e44eaa5aea9776b6cd48f = L.marker(
                [42.310416621645516, -71.08934653172189],
                {}
            ).addTo(map_573f4e54306a4a1ca900cc7b86a142f5);
        
    
            var icon_a575a1068ccf40cab30c193225034b83 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "usd", "iconColor": "white", "iconSize": [27, 27], "markerColor": "purple", "prefix": "glyphicon"}
            );
            marker_99eef5908f4e44eaa5aea9776b6cd48f.setIcon(icon_a575a1068ccf40cab30c193225034b83);
        
    
        var popup_9a1e2624772a459fa6a5541d886a4ec8 = L.popup({"autopan": "False", "maxWidth": "100%"});

        
            var html_cea159ad1d8b4088bbc036dcdf0f8e1e = $(`<div id="html_cea159ad1d8b4088bbc036dcdf0f8e1e" style="width: 100.0%; height: 100.0%;">The G| Code House,  43 Hutchings Street in Roxbury, MA </div>`)[0];
            popup_9a1e2624772a459fa6a5541d886a4ec8.setContent(html_cea159ad1d8b4088bbc036dcdf0f8e1e);
        

        marker_99eef5908f4e44eaa5aea9776b6cd48f.bindPopup(popup_9a1e2624772a459fa6a5541d886a4ec8)
        ;

        
    
</script>

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/AvonleaFisher/Mapping-Boston-Black-Owned-Businesses/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

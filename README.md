index.html ini akan menampilkan box atau kotak dengan gradasi warna. Gradasi ini dilakukan 
dengan menambah CSS di class .box. Ini saya lakukan dalam proses memahami CSS. Materi front end yang saya geluti saat ini. 
Penambahan CSS untuk >> 
1. .box:

   .box {
            width: 300px;
            height: 550px;
            background: rgba(73, 155, 234, 0.82);
            background: -moz-linear-gradient(left, rgba(73, 155, 234, 0.82) 0%, rgba(53, 140, 232, 0.82) 49%, rgba(32, 124, 229, 1) 100%);
            background: -webkit-gradient(left top, right top, color-stop(0%, rgba(73, 155, 234, 0.82)), color-stop(49%, rgba(53, 140, 232, 0.82)), color-stop(100%, rgba(32, 124, 229, 1)));
            background: -webkit-linear-gradient(left, rgba(73, 155, 234, 0.82) 0%, rgba(53, 140, 232, 0.82) 49%, rgba(32, 124, 229, 1) 100%);
            background: -o-linear-gradient(left, rgba(73, 155, 234, 0.82) 0%, rgba(53, 140, 232, 0.82) 49%, rgba(32, 124, 229, 1) 100%);
            background: -ms-linear-gradient(left, rgba(73, 155, 234, 0.82) 0%, rgba(53, 140, 232, 0.82) 49%, rgba(32, 124, 229, 1) 100%);
            background: linear-gradient(to right, rgba(73, 155, 234, 0.82) 0%, rgba(53, 140, 232, 0.82) 49%, rgba(32, 124, 229, 1) 100%);
            filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#499bea', endColorstr='#207ce5', GradientType=1);
            margin: auto;
            margin-top: 120px;
            border-radius: 7px 7px 7px 7px;
            -moz-border-radius: 7px 7px 7px 7px;
            -webkit-border-radius: 7px 7px 7px 7px;
            border: 0px solid #000000;
        }
2.  .box:hover {
            transition: 0.8s all;
            -webkit-box-shadow: 1px 2px 14px -1px rgba(0, 0, 0, 0.75);
            -moz-box-shadow: 1px 2px 14px -1px rgba(0, 0, 0, 0.75);
            box-shadow: 1px 2px 14px -1px rgba(0, 0, 0, 0.75);
            border-radius: 26px 26px 26px 26px;
            -moz-border-radius: 26px 26px 26px 26px;
            -webkit-border-radius: 26px 26px 26px 26px;
            border: 0px solid #000000;
        }

3. h2        
        h2 {
            text-align: center;

        }

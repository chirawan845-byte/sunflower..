```html
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

    <title>AR Sunflower - Hiro Marker</title>

    <!-- A-Frame -->
    <script src="https://aframe.io/releases/1.4.2/aframe.min.js"></script>

    <!-- AR.js -->
    <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar.js"></script>

    <style>
        body {
            margin: 0;
            overflow: hidden;
        }

        #info {
            position: fixed;
            top: 15px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 10;

            color: white;
            background: rgba(0,0,0,0.55);
            padding: 10px 18px;
            border-radius: 20px;

            font-family: Arial, sans-serif;
            font-size: 15px;

            text-align: center;
        }
    </style>
</head>

<body>

<div id="info">
    🌻 ส่องกล้องไปที่ Hiro Marker
</div>


<a-scene
    embedded
    vr-mode-ui="enabled: false"
    renderer="antialias: true; alpha: true"
    arjs="sourceType: webcam; debugUIEnabled: false;"
>

    <!-- แสง -->
    <a-entity light="type: ambient; intensity: 1.2"></a-entity>

    <a-entity
        light="type: directional; intensity: 1.5"
        position="2 4 3">
    </a-entity>


    <!-- Hiro Marker -->
    <a-marker
        preset="hiro"
        id="hiroMarker"
        smooth="true"
        smoothCount="10"
        smoothTolerance="0.01"
        smoothThreshold="5">


        <!-- ======================== -->
        <!-- ดอกทานตะวันทั้งหมด -->
        <!-- ======================== -->

        <a-entity
            id="sunflower"
            position="0 0.15 0"
            scale="0.7 0.7 0.7">


            <!-- ก้าน -->
            <a-cylinder
                position="0 0.6 0"
                radius="0.045"
                height="1.2"
                color="#3b8f32">
            </a-cylinder>


            <!-- ใบซ้าย -->
            <a-entity
                position="-0.18 0.65 0"
                rotation="0 0 -35">

                <a-sphere
                    scale="0.25 0.08 0.12"
                    color="#4caf50">
                </a-sphere>

            </a-entity>


            <!-- ใบขวา -->
            <a-entity
                position="0.18 0.48 0"
                rotation="0 0 35">

                <a-sphere
                    scale="0.25 0.08 0.12"
                    color="#4caf50">
                </a-sphere>

            </a-entity>


            <!-- ======================== -->
            <!-- ส่วนหัวดอก -->
            <!-- ======================== -->

            <a-entity
                id="flower"
                position="0 1.25 0">


                <!-- กลุ่มกลีบทั้งหมด -->
                <a-entity id="petals">


                    <!-- กลีบ 1 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 0">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFD21F">
                        </a-sphere>

                    </a-entity>


                    <!-- กลีบ 2 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 30">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFC107">
                        </a-sphere>

                    </a-entity>


                    <!-- กลีบ 3 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 60">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFD21F">
                        </a-sphere>

                    </a-entity>


                    <!-- กลีบ 4 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 90">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFC107">
                        </a-sphere>

                    </a-entity>


                    <!-- กลีบ 5 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 120">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFD21F">
                        </a-sphere>

                    </a-entity>


                    <!-- กลีบ 6 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 150">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFC107">
                        </a-sphere>

                    </a-entity>


                    <!-- กลีบ 7 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 180">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFD21F">
                        </a-sphere>

                    </a-entity>


                    <!-- กลีบ 8 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 210">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFC107">
                        </a-sphere>

                    </a-entity>


                    <!-- กลีบ 9 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 240">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFD21F">
                        </a-sphere>

                    </a-entity>


                    <!-- กลีบ 10 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 270">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFC107">
                        </a-sphere>

                    </a-entity>


                    <!-- กลีบ 11 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 300">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFD21F">
                        </a-sphere>

                    </a-entity>


                    <!-- กลีบ 12 -->
                    <a-entity
                        class="petal"
                        rotation="0 0 330">

                        <a-sphere
                            position="0 0.30 0"
                            scale="0.13 0.35 0.07"
                            color="#FFC107">
                        </a-sphere>

                    </a-entity>

                </a-entity>


                <!-- เกสรตรงกลาง -->
                <a-sphere
                    position="0 0 0.08"
                    radius="0.24"
                    color="#5D3515">
                </a-sphere>


                <!-- จุดเล็ก ๆ ของเกสร -->
                <a-sphere
                    position="0 0 0.30"
                    radius="0.18"
                    color="#8B5A20">
                </a-sphere>

            </a-entity>

        </a-entity>


        <!-- ================================= -->
        <!-- กลีบที่หลุดออกมา -->
        <!-- ================================= -->

        <a-entity
            id="fallingPetal1"
            position="0 1.45 0"
            visible="false">

            <a-sphere
                scale="0.10 0.25 0.05"
                color="#FFD21F">
            </a-sphere>

        </a-entity>


        <a-entity
            id="fallingPetal2"
            position="0 1.45 0"
            visible="false">

            <a-sphere
                scale="0.10 0.25 0.05"
                color="#FFC107">
            </a-sphere>

        </a-entity>


        <a-entity
            id="fallingPetal3"
            position="0 1.45 0"
            visible="false">

            <a-sphere
                scale="0.10 0.25 0.05"
                color="#FFD21F">
            </a-sphere>

        </a-entity>


    </a-marker>


    <!-- กล้อง AR -->
    <a-entity camera></a-entity>

</a-scene>


<script>

    const marker = document.querySelector('#hiroMarker');
    const flower = document.querySelector('#flower');

    const fallingPetal1 = document.querySelector('#fallingPetal1');
    const fallingPetal2 = document.querySelector('#fallingPetal2');
    const fallingPetal3 = document.querySelector('#fallingPetal3');

    let animationStarted = false;


    // เมื่อพบ Hiro Marker
    marker.addEventListener('markerFound', function () {

        console.log("พบ Hiro Marker");

        animationStarted = true;

        // ให้ดอกหมุน
        flower.setAttribute(
            'animation',
            'property: rotation; from: 0 0 0; to: 0 360 0; dur: 5000; loop: true; easing: linear'
        );


        // กลีบหลุดทีละกลีบ
        setTimeout(() => {
            dropPetal(fallingPetal1, -0.25);
        }, 2500);


        setTimeout(() => {
            dropPetal(fallingPetal2, 0.25);
        }, 4000);


        setTimeout(() => {
            dropPetal(fallingPetal3, 0);
        }, 5500);

    });


    // เมื่อเอา Marker ออกจากกล้อง
    marker.addEventListener('markerLost', function () {

        console.log("ไม่พบ Hiro Marker");

        animationStarted = false;

        flower.removeAttribute('animation');

        resetPetal(fallingPetal1);
        resetPetal(fallingPetal2);
        resetPetal(fallingPetal3);

    });


    // ฟังก์ชันทำให้กลีบดอกหลุด
    function dropPetal(petal, x) {

        petal.setAttribute('visible', true);

        petal.setAttribute(
            'position',
            '0 1.45 0'
        );

        petal.setAttribute(
            'animation__fall',
            `
            property: position;
            to: ${x} 0.15 0.15;
            dur: 2500;
            easing: easeInQuad;
            `
        );


        petal.setAttribute(
            'animation__rotate',
            `
            property: rotation;
            to: 0 360 180;
            dur: 2500;
            easing: linear;
            `
        );

    }


    // รีเซ็ตกลีบ
    function resetPetal(petal) {

        petal.removeAttribute('animation__fall');
        petal.removeAttribute('animation__rotate');

        petal.setAttribute(
            'position',
            '0 1.45 0'
        );

        petal.setAttribute(
            'rotation',
            '0 0 0'
        );

        petal.setAttribute(
            'visible',
            false
        );

    }

</script>

</body>
</html>
```
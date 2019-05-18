<!DOCTYPE HTML>
<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <title>Sky War</title>
    <script type="text/javascript" src="simpleGame.js"></script>
    <script type="text/javascript">
        //object
        var scene;
        var plane;
        var ocean;
        var ocean2;
        var clouds;
        var missile;
        var missileEnemy;
        var enemy;
        var enemy2;
        var missileEnemy2;
        var score = 0;

        var NUM_CLOUDS = 2;

        //sound
        var fireMissile;
        var fireMissileEnemy;
        var boom;
        var engine;

        function Plane() {
            tPlane = new Sprite(scene, "plane.gif", 50, 50);
            tPlane.setSpeed(0);
            tPlane.setPosition(400, 550);
            tPlane.hSpeed = 0;

            tPlane.checkKeys = function () {
                if (keysDown[K_LEFT]) {
                    if (this.hSpeed < -15) {
                        this.hSpeed = -15;
                    } else {
                        this.hSpeed -= 2;
                    }
                }

                if (keysDown[K_RIGHT]) {
                    if (this.hSpeed > 15) {
                        this.hSpeed = 15;
                    } else {
                        this.hSpeed += 2;
                    }
                }

                if (keysDown[K_SPACE]) {
                    missile.fire();
                    fireMissile.play();
                }

                this.changeXby(this.hSpeed);
            }

            tPlane.checkGravity = function () {
                if (this.x < 30) {
                    this.setPosition(30, this.y);
                    tPlane.hSpeed = 0;
                }

                if (this.x > 770) {
                    this.setPosition(770, this.y);
                    tPlane.hSpeed = 0;
                }
            }

            return tPlane;
        }

        function Missile() {
            tMissile = new Sprite(scene, "missile.png", 30, 20);
            tMissile.hide();

            tMissile.fire = function () {
                this.show();
                this.setPosition(plane.x, plane.y);
                this.setAngle(-1)
                this.setSpeed(15);
                this.setBoundAction(DIE);
                this.setImage("missile.png");
            }
            return tMissile;
        }

        function Cloud() {
            tCloud = new Sprite(scene, "cloud.gif", 200, 150);
            tCloud.setPosition(Math.random() * 1000, Math.random() * 1000);
            tCloud.setSpeed(0);
            tCloud.addVector(360, -2);

            return tCloud;
        }

        function NewCloud() {
            tCloud = new Sprite(scene, "cloud.gif", 200, 150);
            tCloud.setPosition(Math.random() * 1000, 10);
            tCloud.setSpeed(0);
            tCloud.addVector(360, -2);

            return tCloud;
        }

        function makeClouds() {
            clouds = new Array(NUM_CLOUDS);
            for (i = 0; i < NUM_CLOUDS; i++) {
                clouds[i] = new Cloud();
            }
        }

        function updateClouds() {
            for (i = 0; i < NUM_CLOUDS; i++) {
                clouds[i].update();
            }
        }

        function Enemy() {
            tEnemy = new Sprite(scene, "plane.gif", 50, 50);
            tEnemy.setAngle(270)
            tEnemy.setSpeed(0);
            tEnemy.setPosition(Math.random() * 1000, 0);
            if (score > 9) {
                tEnemy.addVector(360, -5);
            } else if (score > 14) {
                tEnemy.addVector(360, -9);
            } else {
                tEnemy.addVector(360, -3);
            }

            tEnemy.startFire = function () {
                MissileEnemy();
            }

            return tEnemy
        }

        function MissileEnemy() {
            tMissileEnemy = new Sprite(scene, "missile.png", 30, 20);
            tMissileEnemy.show();
            tMissileEnemy.setPosition(enemy.x, enemy.y);
            tMissileEnemy.setAngle(180);
            if (score > 4) {
                tMissileEnemy.setSpeed(10);
            } else if (score > 9) {
                tMissileEnemy.setSpeed(15);
            } else if (score > 14) {
                tMissileEnemy.setSpeed(20);
            } else {
                tMissileEnemy.setSpeed(5);
            }
            tMissileEnemy.setBoundAction(DIE);
            tMissileEnemy.setImage("missile.png");
            fireMissileEnemy.play();

            return tMissileEnemy;
        }

        function Enemy2() {
            tEnemy = new Sprite(scene, "plane.gif", 50, 50);
            tEnemy.show();
            tEnemy.setAngle(270)
            tEnemy.setSpeed(0);
            tEnemy.setPosition(Math.random() * 1000, 0);
            if (score > 9) {
                tEnemy.addVector(360, -5);
            } else if (score > 14) {
                tEnemy.addVector(360, -9);
            } else {
                tEnemy.addVector(360, -3);
            }

            tEnemy.startFire = function () {
                MissileEnemy2();
            }

            return tEnemy
        }

        function MissileEnemy2() {
            tMissileEnemy = new Sprite(scene, "missile.png", 30, 20);
            tMissileEnemy.setPosition(enemy2.x, enemy2.y);
            tMissileEnemy.setAngle(180);
            if (score > 4) {
                tMissileEnemy.setSpeed(10);
            } else if (score > 9) {
                tMissileEnemy.setSpeed(15);
            } else if (score > 14) {
                tMissileEnemy.setSpeed(20);
            } else {
                tMissileEnemy.setSpeed(5);
            }
            tMissileEnemy.setBoundAction(DIE);
            tMissileEnemy.setImage("missile.png");
            fireMissileEnemy.play();

            return tMissileEnemy;
        }

        function Ocean() {
            tOcean = new Sprite(scene, "ocean.jpg", 800, 1440);
            tOcean.setAngle(180);
            tOcean.setSpeed(1);
            tOcean.setPosition(400, 300);

            tOcean.checkBounds = function () {
                if (this.y > 400) {
                    // this.setPosition(400,200)
                    // ocean = new Ocean();
                }
            }

            return tOcean;
        }

        buildSounds = function () {
            fireMissile = new Sound("missile.wav");
            fireMissileEnemy = new Sound("missile.wav");
            boom = new Sound("boom.wav");
            engine = new Sound("engine.wav");
        }

        function Ocean2() {
            tOcean = new Sprite(scene, "ocean.jpg", 800, 1440);
            tOcean.setAngle(180);
            tOcean.setSpeed(1);
            tOcean.setPosition(400, -500.50);

            tOcean.checkBounds = function () {

                if (this.y > 300) {
                    ocean = new Ocean();
                    ocean2 = new Ocean2();
                }
            }

            return tOcean;
        }

        function checkCollision() {
            if (missile.collidesWith(enemy)) {
                boom.play();
                enemy.hide();
                missile.hide();
                updateScore();
                enemy = new Enemy();
                missileEnemy = new MissileEnemy();
            }

            if (missile.collidesWith(enemy2)) {
                boom.play();
                enemy2.hide();
                missile.hide();
                updateScore();
                enemy2 = new Enemy2();
                missileEnemy2 = new MissileEnemy2();
            }

            if (enemy.y > 580) {
                enemy.hide();
                enemy = new Enemy();
                missileEnemy = new MissileEnemy();
            }

            if(enemy2.y > 580){
                enemy2.hide();
                enemy2 = new Enemy2();
                missileEnemy2 = new MissileEnemy2();
            }

            for (var i = 0; i < NUM_CLOUDS; i++) {
                if (clouds[i].y > 580) {
                    clouds[i].hide();
                    clouds[i] = new NewCloud();
                }
            }

            if (plane.collidesWith(enemy) || missileEnemy.collidesWith(plane) || plane.collidesWith(enemy2) || missileEnemy2.collidesWith(plane)) {
                enemy.hide();
                missileEnemy.hide();
                enemy2.hide();
                missileEnemy2.hide();
                gameOver();
            }

        }

        function gameOver() {
            alert("You Lose");
            window.location.href = ""
        }

        function updateScore() {
            score++;
            var showScore = document.getElementById('score');
            showScore.innerHTML = "Score : " + score;
        }

        function init() {
            buildSounds();
            scene = new Scene();
            plane = new Plane();
            missile = new Missile();
            enemy = new Enemy();
            missileEnemy = new MissileEnemy();
            enemy2 = new Enemy2();
            missileEnemy2 = new MissileEnemy2();
            makeClouds();
            ocean = new Ocean();
            ocean2 = new Ocean2();

            scene.start();
        }

        function update() {
            engine.play();
            scene.clear();

            plane.checkKeys();
            plane.checkGravity();
            checkCollision()


            ocean.update();
            ocean2.update();
            updateClouds();
            enemy.update();
            if (score > 9) {
                enemy2.update();
                missileEnemy2.update();
            }
            missile.update();
            plane.update();
            missileEnemy.update();
        }
    </script>
</head>

<body onload="init()">
    <div id="score" style="font-size: 40px;">Score : 0</div>
</body>

</html>
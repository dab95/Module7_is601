# Module 7


## QR Code for Github Repository

![GithubRepository] (/qr_codes/QRCode_20251028015643.png "My QR Code Link")

   ## Overriding Default URL
<!-- (venv) diegob@MacBookAir module7_is601 % docker run -v ./qr_codes:/app/qr_codes dab95/module7.qr_codemaker --url https://github.com/dab95/Module7_is601             

2025-10-28 01:56:43,940 - INFO - QR code successfully saved to /app/qr_codes/QRCode_20251028015643.png -->

   ## docker compose yml 'command'
<!-- (venv) diegob@MacBookAir module7_is601 % docker compose up                        
WARN[0000] /Users/diegob/is601/projects/module7_is601/docker-compose.yml: the attribute `version` is obsolete, it will be ignored, please remove it to avoid potential confusion 
[+] Running 1/1
 ✔ Container module7_is601-qr_code_app-1  Recreated                                                    0.1s 
Attaching to qr_code_app-1
qr_code_app-1  | 2025-10-28 01:58:26,453 - INFO - QR code successfully saved to /app/qr_codes/QRCode_20251028015826.png
qr_code_app-1 exited with code 0 -->


## QR Code for Docker Image

![DockerRepository] (qr_codes/QRCode_20251028015702 "My QR Code Link")

   ## input overriding default url
<!-- (venv) diegob@MacBookAir module7_is601 % docker run -v ./qr_codes:/app/qr_codes dab95/module7.qr_codemaker --url https://hub.docker.com/r/dab95/module7.qr_codemaker

2025-10-28 01:57:02,487 - INFO - QR code successfully saved to /app/qr_codes/QRCode_20251028015702.png -->

   ## docker compose yml 'command' 
<!-- (venv) diegob@MacBookAir module7_is601 % docker compose up
WARN[0000] /Users/diegob/is601/projects/module7_is601/docker-compose.yml: the attribute `version` is obsolete, it will be ignored, please remove it to avoid potential confusion 
[+] Running 1/1
 ✔ Container module7_is601-qr_code_app-1  Recreated                                                    0.2s 
Attaching to qr_code_app-1
qr_code_app-1  | 2025-10-28 01:59:51,247 - INFO - QR code successfully saved to /app/qr_codes/QRCode_20251028015951.png
qr_code_app-1 exited with code 0 -->


## DOCKER LOGS
<!-- (venv) diegob@MacBookAir module7_is601 % docker logs 267a65cb503a
2025-10-28 01:56:43,940 - INFO - QR code successfully saved to /app/qr_codes/QRCode_20251028015643.png
(venv) diegob@MacBookAir module7_is601 % docker logs cdf32ed848bf
2025-10-28 01:57:02,487 - INFO - QR code successfully saved to /app/qr_codes/QRCode_20251028015702.png
(venv) diegob@MacBookAir module7_is601 % docker logs cdf32ed848bf
2025-10-28 01:57:02,487 - INFO - QR code successfully saved to /app/qr_codes/QRCode_20251028015702.png
(venv) diegob@MacBookAir module7_is601 % docker logs 04c51ca20626
2025-10-28 01:59:51,247 - INFO - QR code successfully saved to /app/qr_codes/QRCode_20251028015951.png
(venv) diegob@MacBookAir module7_is601 %  -->

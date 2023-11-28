# DDoS-detection-and-Mitigation-using-Machine-Learning
Detection and Mitigation System Against DDoS Attacks in Software-Defined Networks

Find dataset here: https://drive.google.com/file/d/1N2QLDPb90XOdxcuQ_Fb7ZSVOG4J3w_zY/view?usp=sharing

Find ryu controller vm here: https://drive.google.com/file/d/1_5PQWBsQcVnxtzwhUMzP-w2mR9MZrG6S/view?usp=sharing

Find miniet vm here: https://drive.google.com/file/d/1H7Hs-yruNQKMDmcdgHJGHIDtopPNFAvH/view?usp=sharing

Steps:
Import virtual machines to virtualbox

Change ip address of ryu controller in source code

On ryu controller run: ryu-manager DT_controller.py

On mininet run: sudo python topology.py

Launch DDoS attacks as decribed in youtube videos and see results.

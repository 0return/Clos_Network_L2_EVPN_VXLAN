L2 EVPN/VXLAN Clos Network Lab

A hands-on Layer 2 EVPN/VXLAN lab built with Nokia SR Linux 25.7 and Containerlab.

The lab demonstrates how EVPN is used as the control plane for a VXLAN overlay in a Clos leaf-spine topology, providing Layer 2 connectivity between hosts attached to different leaf switches.

The main objective is to demonstrate how multiple customers can share the same physical infrastructure while remaining logically isolated through separate MAC-VRFs and VXLAN VNIs.

Topology:


<img width="1272" height="449" alt="image" src="https://github.com/user-attachments/assets/76f0733d-fb47-4036-a8bf-a12c56b5dded" />




Verification commands:

Spine´s commands:

<img width="1310" height="603" alt="image" src="https://github.com/user-attachments/assets/8586192c-970c-4cdd-ba08-051dfe165483" />

<img width="1273" height="364" alt="image" src="https://github.com/user-attachments/assets/f63d6a28-c851-4d2c-bbe9-7731161137dc" />

<img width="1567" height="621" alt="image" src="https://github.com/user-attachments/assets/dc3705b9-1718-4bd9-b2c2-349253ae7a12" />



Leaf´s commands:

<img width="1475" height="405" alt="image" src="https://github.com/user-attachments/assets/ccf274d6-a5a7-42e5-8985-98ad8c35c82c" />

<img width="1467" height="410" alt="image" src="https://github.com/user-attachments/assets/94b3d464-5e27-436b-bd8c-a82c27520e72" />

<img width="634" height="332" alt="image" src="https://github.com/user-attachments/assets/7b517d53-2a79-49be-895e-15589b42612e" />

<img width="583" height="596" alt="image" src="https://github.com/user-attachments/assets/60c2809d-1e4f-4cba-b776-f18282e48dfb" />








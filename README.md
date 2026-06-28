# LAB Block-Layer-2-Tunneling-Protocol-L2TP-
Block Layer 2 Tunneling Protocol (L2TP)

•	Select ZYWIN02 from the drop-down menu in the right pane and click Connect to VMs.

•	The following steps create a firewall inbound rule on ZYWIN02 for allowing Internet Control Message Protocol (ICMP) packets.

•	Click Windows Start and select Server Manager.

<img width="626" height="417" alt="Screenshot" src="https://github.com/user-attachments/assets/7fa407c5-0dad-4253-821b-aa42879eb601" />

•	In Server Manager, select Tools → Windows Defender Firewall with Advanced Security

<img width="975" height="552" alt="image" src="https://github.com/user-attachments/assets/593d2c28-5451-4448-a6e3-5b184b7197aa" />

•	Windows Defender Firewall with Advanced Security allows for the management of inbound or outbound firewall rules.

 <img width="975" height="691" alt="image" src="https://github.com/user-attachments/assets/62662e8f-b55b-4f04-bc13-26ac094a3245" />

•	Click on Inbound Rules. Right-click Inbound Rules and select New Rule….

 <img width="955" height="528" alt="image" src="https://github.com/user-attachments/assets/e4cacc51-57ab-4ddf-9a27-db5ae1a73318" />

•	Select Custom and click Next.

 <img width="975" height="794" alt="image" src="https://github.com/user-attachments/assets/1c035021-c9bd-49c8-9093-e891fd6f5613" />

•	Select All Programs and click Next.

<img width="975" height="794" alt="image" src="https://github.com/user-attachments/assets/0284c849-8443-4a39-a8f3-a4485b82d047" />

•	Select L2TP for protocol type

<img width="992" height="882" alt="Screenshot L2TP" src="https://github.com/user-attachments/assets/86691b4d-44b2-42ca-9ccf-2c1f343d9f8d" />


•	Click Next.

<img width="975" height="794" alt="image" src="https://github.com/user-attachments/assets/dc94d8f8-24fb-41b4-a598-88a47e3c1872" />

•	Select Block the connection and click Next.

<img width="984" height="824" alt="Screenshot L2TP BLOCK" src="https://github.com/user-attachments/assets/8184bc10-5a76-4cd1-a9a6-9268e20336f3" />

•	Click Next.

<img width="975" height="794" alt="image" src="https://github.com/user-attachments/assets/8ecd1b30-c4f6-4c2e-a50b-ff3502460baa" />

•	Enter L2TP in the Name field and click Finish.

<img width="984" height="811" alt="Screenshot 2026-06-28 183831" src="https://github.com/user-attachments/assets/5f7150dc-b928-4c2b-8e90-571e219e6c7c" />

•	The L2TP rule is displayed in inbound rules.

<img width="957" height="407" alt="Screenshot 2026-06-28 192444" src="https://github.com/user-attachments/assets/d01ca2bd-abf1-48f3-8ef8-ea8ddf9e3528" />


•L2TP inbound rule created and enabled.

•	In the right pane select ZYWIN01. In ZYWIN01, click Windows Start and select Windows PowerShell.

<img width="975" height="648" alt="image" src="https://github.com/user-attachments/assets/022cd3c7-4f8c-4863-91ba-d363cf3a96e0" />

•	Run the ping command with destination device ZYWIN02.

•	ping ZYWIN02

•	ping is successful because the L2TP inbound rule on ZYWIN02 blocks ICMP messages.

<img width="1005" height="706" alt="Screenshot 2026-06-28 184228" src="https://github.com/user-attachments/assets/488318af-3afb-43db-91ec-d9a8aa02f9b0" />

•	ping ZYWIN02 executed.

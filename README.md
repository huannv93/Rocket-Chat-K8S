# Rocket-Chat-K8S

- B1': Tao NFS server
- B1: Tao PV
- B2 : Tao PVC
- B3: chay Deployment mongo-init first
- B4: Chay Deployment mongo-db
- B5: Chay Deployment rocket-chat services
- B6: Chay rocket-chat services : metalLB

// Nghien cứu depend on tren K8S
- theo tim hieu thi ko có depends on trên k8s
- xử lý bằng cach chạy vài câu lệnh linux trong config deployment để set services nào start trc
- 

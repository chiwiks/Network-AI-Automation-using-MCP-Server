## 🔥 Troubleshooting
- [x] Scenario 1
```
Change the mtu of ethernet1 of R1. This will move the ospf neiggbor from FULL adjacency to ExStart.
```
<img width="521" height="49" alt="Image" src="https://github.com/user-attachments/assets/0b4c1f7d-b837-4004-928f-3f304b5ad9ab" />

```
Ask Claude to check and fix the issue
```

- [x] Scenario 2
```
Add Switchport to interface Ethernet1 of R1 with bring down the ospf neighbor because on Arista that will switch the interface to L2
```
<img width="505" height="77" alt="Image" src="https://github.com/user-attachments/assets/9b18be6d-dc70-47be-83d3-fe210270fcf4" />
```
Next ask Claude to troubleshoot and fix the issue

```

- [x] Scenario 3
```
Change mtu size and Bring down the interface with "shutdown" and ask Claude to fix it
```
Claude recognizes both issues and brings up the interface and fixes the mtu to default fixing the ospf neighbor 

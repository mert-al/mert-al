- š Hi, Iām @mert-al
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on cd
- š« How to reach me ...d

<!---
mert-al/mert-al is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def TowerOfHanoi(n , from_rod, to_rod, aux_rod):
    if n == 1:
        print("Move disk 1 from rod",from_rod,"to rod",to_rod)
        return
    TowerOfHanoi(n-1, from_rod, aux_rod, to_rod)
    print("Move disk",n,"from rod",from_rod,"to rod",to_rod)
    TowerOfHanoi(n-1, aux_rod, to_rod, from_rod)
         

n = int(input("Enter the number of disks"))
TowerOfHanoi(n, 'A', 'C', 'B')def TowerOfHanoi(n , from_rod, to_rod, aux_rod):
    if n == 1:
        print("Move disk 1 from rod",from_rod,"to rod",to_rod)
        return
    TowerOfHanoi(n-1, from_rod, aux_rod, to_rod)
    print("Move disk",n,"from rod",from_rod,"to rod",to_rod)
    TowerOfHanoi(n-1, aux_rod, to_rod, from_rod)
         

n = int(input("Enter the number of disks"))
TowerOfHanoi(n, 'A', 'C', 'B')

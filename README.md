Windows-Command
==========
####Fix Pendrive & Bootable
<pre>
cmd
diskpart
list disk
Select Disk 1
Clean
Create Partition Primary
Select Partition 1
Active
Format FS=NTFS
Assign
Exit
</pre>

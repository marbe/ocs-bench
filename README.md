This files are used to test OCS 3 (gluster) performences with iozone.

You can create pvc, create pods and the run some test within pvc mount point:

 * iozone -r 8k -s 1g -t 2 -b /usr/share/gluster/report_block_infra_8k.xls . 
 * iozone -r 64k -s 1g -t 2 -b /usr/share/gluster/report_block_infra_64k.xls . 
 * iozone -r 128k -s 1g -t 2 -b /usr/share/gluster/report_block_infra_128k.xls . 
 * iozone -r 256k -s 1g -t 2 -b /usr/share/gluster/report_block_infra_256k.xls . 

Here you can find more details:

 * https://access.redhat.com/solutions/32138



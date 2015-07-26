# showstate

a tool to view disk overview with some informations like this

simple call
```
-------------------------------------------------------------------------------------
#       Disk #          State #   Total #    Used #    Free #       Mounted #  Temp
-------------------------------------------------------------------------------------
#   /dev/sda #    active/idle #    113G #     15G #     93G #             / #     - #
#   /dev/sdb #        standby #    3,6T #    3,5T #     95G #       /mnt/d4 #     - #
#   /dev/sdc #        standby #    3,6T #    3,1T #    485G #       /mnt/d3 #     - #
#   /dev/sdd #        standby #    2,7T #    2,5T #    205G #       /mnt/d5 #     - #
#   /dev/sde #        standby #    2,7T #    2,7T #     85G #       /mnt/d1 #     - #
#   /dev/sdf #        standby #    2,7T #    2,5T #    245G #       /mnt/d2 #     - #
#   /dev/sdg #        standby #    3,6T #    3,5T #    175G #  /mnt/parity1 #     - #
#   /dev/sdh #        standby #    2,7T #    2,4T #    325G #       /mnt/d6 #     - #
#   /dev/sdi #        standby #    3,6T #    3,5T #    175G #       /mnt/d7 #     - #
-------------------------------------------------------------------------------------
```

with --smart
```
------------------------------------------------------------------------------------------------
#       Disk #          State #   Total #    Used #    Free #       Mounted #  Temp #  PowerOn
------------------------------------------------------------------------------------------------
#   /dev/sda #    active/idle #    113G #     15G #     93G #             / #     - #     2924 #
#   /dev/sdb #        standby #    3,6T #    3,5T #     95G #       /mnt/d4 #     - #        - #
#   /dev/sdc #        standby #    3,6T #    3,1T #    485G #       /mnt/d3 #     - #        - #
#   /dev/sdd #        standby #    2,7T #    2,5T #    205G #       /mnt/d5 #     - #        - #
#   /dev/sde #        standby #    2,7T #    2,7T #     85G #       /mnt/d1 #     - #        - #
#   /dev/sdf #    active/idle #    2,7T #    2,5T #    245G #       /mnt/d2 #    24 #     4821 #
#   /dev/sdg #        standby #    3,6T #    3,5T #    175G #  /mnt/parity1 #     - #        - #
#   /dev/sdh #        standby #    2,7T #    2,4T #    325G #       /mnt/d6 #     - #        - #
#   /dev/sdi #        standby #    3,6T #    3,5T #    175G #       /mnt/d7 #     - #        - #
------------------------------------------------------------------------------------------------
```

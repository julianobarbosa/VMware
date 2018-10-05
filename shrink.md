# Shrink

## Formula:
```console
        Disk Size: 50 GB
    Extent size: Disk Size(GB) * 1024 * 1024 * 1024/512
    Extent size: 50 * 1024 * 1024 * 1024/512 = 104857600
        Shrink Size: 10 GB
    Shrink Size: 10 * 1024 * 1024 * 1024/512 = 20971520

        Final Disk size = 40 GB
    Final Size: 104857600 - 20971520 = 83886080

        Reverse Disk size:
        83886080 / 1024 / 1024 / 1024 * 512 = 40
```


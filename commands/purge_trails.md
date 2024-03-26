If you want to delete trails by hand you can run this in adminclient:

    PURGE EXTTRAIL PATH

For OCI GoldenGate you can run PURGE EXTTRAIL `/u02/Deployment/var/lib/data/TRAIL_DIR` (if you use a trail directory parameter) the fully qualified path  `/u02/Deployment/var/lib/data/XX00001` (where XX0001 is the trail name) or a wildcard `/u02/Deployment/var/lib/data/XX00001` .

**### But pay attention because the trail shouln't be in use for the Extract process and if you use an wildcard it will DELETE ALL TRAILS.**

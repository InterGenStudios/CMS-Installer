![alt text](https://intergenstudios.com/Downloads/cms-inst.png "CMS Installer")

---

### Command line CMS installer for CentOS 6+ servers running WHM/cPanel
---

Server root pass is required for use

#### To use:

```
mkdir -p /root/support && cd /root/support
wget https://raw.githubusercontent.com/InterGenStudios/CMS-Installer/master/instcms
chmod +x instcms
echo alias instcms=\'/bin/bash /root/support/instcms\' >> ~/.bashrc
/bin/bash /root/support/instcms -h
source ~/.bashrc
```



```

- To do list:
  1) Start cPanel Plugin GUI Development
  2) Identify and integrate additional CMSs
  3) Everything else  
```

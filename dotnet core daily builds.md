# How to install/update daily .NET Core builds

##### install prerequisites
``apt-get install curl libunwind8 gettext``

##### download latest build for your platform (e.g. ``armhf``) from here: [Daily Builds](https://github.com/dotnet/core-setup#daily-builds)

``curl -sSL -o dotnet-master.tar.gz https://dotnetcli.blob.core.windows.net/dotnet/Runtime/master/dotnet-runtime-latest-linux-arm.tar.gz``

##### extract

```
mkdir -p /opt/dotnet-master
tar zxf dotnet-master.tar.gz -C /opt/dotnet-master
```

##### set up symbolic link
``ln -s /opt/dotnet-master/dotnet /usr/local/bin``

##### test
``dotnet --info``

Source: https://blogs.msdn.microsoft.com/david/2017/07/20/setting_up_raspian_and_dotnet_core_2_0_on_a_raspberry_pi/

![IAB Tech Lab](https://drive.google.com/uc?id=10yoBoG5uRETSXRrnJPUDuONujvADrSG1)

# **OpenDirect Extensions**


#### What is the lifecycle of an Extension?
When individual companies want to solve a problem that isn't covered by the core OpenDirect (or AdCOM) specs, they can use OpenDirect's (and/or AdCOM's) extensions mechanism to implement a solution. They can work on it privately and limit usage between themselves, or they can make the OpenDirect "Community" aware of this extension to guage the usefulness of that extension. 

After a period of time, if there is sufficient support, the extension can be made part of the "official" specs by getting approval from the Programmatic Supply Chain Working Group. This path is slightly different for OpenDirect 1.x and 2.x: The Working Group has decided that there will be no more updates to 1.x, so with 1.x, the extension gets moved to the "1.x_OfficialExtensions" folder. For 2.x the extension gets merged to the OpenDirect/AdCOM specs and released as a new version of the specs.

![extensions lifecycle](extensions_lifecycle-opendirect.png)



#### How do I submit a "community extension"?
1. Submit an issue on the github repository for OpenDirect or AdCOM depending on where your extension belongs. (If you are submitting a 1.x extension, it belongs to OpenDirect. For 2.x, it will depend on what you are trying to "extend").
2. Submit a PR associated with that issue, with files in the [extensions/community_extensions](../extensions/community_extensions) folder. Also include an entry in the [extensions/community_extensions/README.md](../extensions/community_extensions/README.md).

#### How do I get a community extension formally adopted into the specs?
1. Submit an issue and PR with the desired changes on the github repository for OpenDirect (and/or AdCOM).
2. Email us at openmedia@iabtechlab.com with any information not in the issue/PR, including any  adoption information for the community extension. 
3. We will discuss in the Programmatic Supply Chain Working Group and (assuming you are a Tech Lab member), invite you to present.
4. Once approved, the extension will be either moved to the [extensions/1.x_official_extensions](../extensions/1.x_official_extensions) folder or made a part of the 2.x specs (to be released with the next official version of the specs).

#### Where are the current community extensions?
You can find the current extensions in the [extensions/community_extensions](../extensions/community_extensions) folder.

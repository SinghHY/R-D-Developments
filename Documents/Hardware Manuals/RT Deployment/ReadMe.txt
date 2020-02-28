LabVIEW 7.1 or higher is required
Internet Toolkit is required

To install the VI's to a System Replication Palette under the User Libraries section of the LabVIEW Palette, copy the following files:

RepControls.llb
SubVIs.llb
dir.mnu
SystemReplication.llb

into C:\Program Files\National Instruments\LabVIEW N.n\user.lib\SystemReplication

where N.n depends on which version of LabVIEW you are using.

Recent Changes:

12/12/2006: Replication Tools no longer require that LabVIEW Real-Time is installed on the development machine. 
Replication tools now compatible with Linux and Mac OS X.

4/11/2007: Example program RTCopy.vi/RTCP.exe no longer has strict target checking using the Verify Target ID input of
Set Target Image.vi.
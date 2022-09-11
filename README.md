## How to get latest commit in Mono for the current Unturned version
- Clone [mono](https://github.com/Unity-Technologies/mono).
- By clicking to the options of Unturned.exe you could see the version there.
- Select branch that similar to the Unturned version from the second step.
- Use [umpatcher](https://github.com/dnSpy/dnSpy-Unity-mono#supporting-a-new-unity-version-for-dummies) or read PE yourself to get the timestamp from Unturned\MonoBleedingEdge\EmbedRuntime\mono-2.0-bdwgc.dll
- The last step is find the commit with the your unturned version branch in [mono](https://github.com/Unity-Technologies/mono) repository that almost/absolutely equals to your timestamp.

# Commit hashes 
version | git hash | files | latest
--------|----------|-------|-------
unity-2020.3-mbe | ec4662b80b585e66487c39f199621aa0e82844f0 | https://github.com/Unity-Technologies/mono/tree/ec4662b80b585e66487c39f199621aa0e82844f0 | +
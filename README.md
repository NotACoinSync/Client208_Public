# GMS v208.3
MapleStory Localhost Project - Originally released on rebirth.dev

Fork this project and replace the method on the specified line
https://github.com/RajanGrewal/Client176/blob/master/AuthHook/Client176/MapleHook.cpp#L4

## Values
```
void FuckMaple()
{
	Log(__FUNCTION__);

	//NGS Removal
	PatchRetZero(0x02B201C0);
  
	//MSCRC Bypass
	PatchJmp(0x02B2F8F6, 0x02B2F98A);
}
```

## Launch Arguments
`MapleStory.exe WebStart SomeWebTokenHereFromALauncher`

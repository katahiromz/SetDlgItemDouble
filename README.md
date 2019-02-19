# SetDlgItemDouble

```c
#include "SetDlgItemDouble.h"
__inline double WINAPI
GetDlgItemDouble(HWND hDlg, int nItemID, BOOL *pbTranslated);
__inline BOOL WINAPI
SetDlgItemDouble(HWND hDlg, int nItemID, double eValue, const char *fmt);

__inline float WINAPI
GetDlgItemFloat(HWND hDlg, int nItemID, BOOL *pbTranslated);
#define SetDlgItemFloat SetDlgItemDouble
```

License: MIT

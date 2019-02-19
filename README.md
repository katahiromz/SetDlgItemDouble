# SetDlgItemDouble

```c
#include "SetDlgItemDouble.h"
__inline double WINAPI
GetDlgItemDouble(HWND hDlg, int nItemID, BOOL *pbTranslated OPTIONAL);
__inline BOOL WINAPI
SetDlgItemDouble(HWND hDlg, int nItemID, double eValue, const char *fmt OPTIONAL);

__inline float WINAPI
GetDlgItemFloat(HWND hDlg, int nItemID, BOOL *pbTranslated OPTIONAL);
#define SetDlgItemFloat SetDlgItemDouble
```

License: MIT

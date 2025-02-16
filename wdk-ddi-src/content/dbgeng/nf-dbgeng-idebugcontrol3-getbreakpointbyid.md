---
UID: NF:dbgeng.IDebugControl3.GetBreakpointById
title: IDebugControl3::GetBreakpointById (dbgeng.h)
description: The GetBreakpointById method returns the breakpoint with the specified breakpoint ID. This method belongs to the IDebugControl3 interface.
old-location: debugger\getbreakpointbyid.htm
tech.root: debugger
ms.date: 05/03/2018
keywords: ["IDebugControl3::GetBreakpointById"]
ms.keywords: GetBreakpointById, GetBreakpointById method [Windows Debugging], GetBreakpointById method [Windows Debugging],IDebugControl interface, GetBreakpointById method [Windows Debugging],IDebugControl2 interface, GetBreakpointById method [Windows Debugging],IDebugControl3 interface, IDebugControl interface [Windows Debugging],GetBreakpointById method, IDebugControl2 interface [Windows Debugging],GetBreakpointById method, IDebugControl2::GetBreakpointById, IDebugControl3 interface [Windows Debugging],GetBreakpointById method, IDebugControl3.GetBreakpointById, IDebugControl3::GetBreakpointById, IDebugControl::GetBreakpointById, IDebugControl_641f8e32-6c08-4b63-89c6-877b52a86ab2.xml, dbgeng/IDebugControl2::GetBreakpointById, dbgeng/IDebugControl3::GetBreakpointById, dbgeng/IDebugControl::GetBreakpointById, debugger.getbreakpointbyid
req.header: dbgeng.h
req.include-header: Dbgeng.h
req.target-type: Desktop
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
f1_keywords:
 - IDebugControl3::GetBreakpointById
 - dbgeng/IDebugControl3::GetBreakpointById
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - dbgeng.h
api_name:
 - IDebugControl3::GetBreakpointById
---

# IDebugControl3::GetBreakpointById


## -description

The <b>GetBreakpointById</b>  method returns the breakpoint with the specified breakpoint ID.

## -parameters

### -param Id 

[in]
Specifies the breakpoint ID of the breakpoint to return.

### -param Bp 

[out]
Receives the breakpoint.

## -returns

This method can also return other error values.  See <a href="/windows-hardware/drivers/debugger/hresult-values">Return Values</a> for more details.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method was successful.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_NOINTERFACE</b></dt>
</dl>
</td>
<td width="60%">
No breakpoint was found with the given ID, or the breakpoint with the specified ID does not belong to the current process, or the breakpoint with the given ID is private (see <a href="/windows-hardware/drivers/ddi/dbgeng/nf-dbgeng-idebugbreakpoint2-getflags">GetFlags</a>).

</td>
</tr>
</table>

## -remarks

If the specified breakpoint does not belong to the current process, the method will fail.

## -see-also

<a href="/windows-hardware/drivers/ddi/dbgeng/nn-dbgeng-idebugbreakpoint">IDebugBreakpoint</a>



<a href="/windows-hardware/drivers/ddi/dbgeng/nn-dbgeng-idebugcontrol">IDebugControl</a>



<a href="/windows-hardware/drivers/ddi/dbgeng/nn-dbgeng-idebugcontrol2">IDebugControl2</a>



<a href="/windows-hardware/drivers/ddi/dbgeng/nn-dbgeng-idebugcontrol3">IDebugControl3</a>


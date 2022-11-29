# IDAPython

import ida_dbg
ida_dbg.start_process('','','')

idaapi.get_imagebase()

ida_dbg.del_bpt(addr)

ida_dbg.wait_for_next_event(WFNE_SUSP, -1)
idaapi.continue_process()

idc.set_reg_value(value, regname)
idc.get_reg_value(regname)

ida_bytes.get_bytes
ida_bytes.get_dword

idaapi.patch_bytes(start, data) 

function BAMYT() end
function setvalue(address,flags,value) BAMYT('Modify address value(Address, value type, value to be modified)') local tt={} tt[1]={} tt[1].address=address tt[1].flags=flags tt[1].value=value gg.setValues(tt) end

gg.setVisible(true)
gg.setVisible(true)
LuaLibrary = -1
function HOME()
MENU = gg.multiChoice({
        "▪ FIX 3RD (logo)", 
        "▪ BYPASS (lobby)", 
        "EXIT" 
  }, nil, "ＢＡＭ ＹＴ\n⌛ TANGGAL：" .. Time) if MENU == nil then
  else
   if MENU[1] == true then 
      BAM1()
     end
   if MENU[2] == true then 
      BAM2()
     end
   if MENU[3] == true then
      LOBBY()
     end
   end
  LuaLibraryTool = -1
end

function BAM1() 
RD1 = gg.multiChoice({
"Fix 3RD Virtual Android 11",
"Fix 3RD Virtual DIKIN",
 "Kembali",
}, nil, " Aktifin Di Logo Keadaan Data Mati")
if RD1 == nil then
else
if RD1[1] == true then
RDD1()
end
if RD1[2] == true then
RDD2()
end
if RD1[3] == true then
HOME()
end
end
LuaLibrary = -1 
end

function RDD1()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber(":/data/user/0/com.tencent", gg.TYPE_BYTE)
gg.getResults(90000)
gg.editAll("108", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber(":/data/user/0/com.tencent", gg.TYPE_BYTE)
gg.getResults(90000)
gg.editAll("108", gg.TYPE_BYTE)
gg.clearResults()
gg.alert("Bypass 3RD VIRTUAL Android 11")
end

function RDD2()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber(":com.tencent.iglite.ztf", gg.TYPE_BYTE)
gg.getResults(90000)
gg.editAll("108", gg.TYPE_BYTE)
gg.clearResults()
gg.alert("Bypass 3RD Virtual Android 10")
end

function BAM2() 
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("196,864;16,842,753::5", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1) 
if gg.getResultCount() == 0 then
gg.alert("❌STOP SINYALMU JELEK ULANGI LAGI?")
  gg.processKill()
os.exit()
else
gg.searchNumber("196,864", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
n = gg.getResultCount()
jz = gg.getResults(n)
for i = 1, n do
end
end
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("133634;133634", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("133634", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30000)
gg.editAll("67175425", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("134914;133378", gg.TYPE_DWORD)
gg.refineNumber("134914", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("133378;134658", gg.TYPE_DWORD)
gg.refineNumber("133378", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("67175425", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("133378;144387", gg.TYPE_DWORD)
gg.refineNumber("133378", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("67175425", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("133378;70658", gg.TYPE_DWORD)
gg.refineNumber("133378", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("67175425", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("133378;262403", gg.TYPE_DWORD)
gg.refineNumber("133378", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("67175425", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("133634", gg.TYPE_DWORD)
gg.refineNumber("133634", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("67175425", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("134914;134914", gg.TYPE_DWORD)
gg.refineNumber("134914", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("134914;131586", gg.TYPE_DWORD)
gg.refineNumber("134914", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("131330;134402", gg.TYPE_DWORD)
gg.refineNumber("134402", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("134914;135682", gg.TYPE_DWORD)
gg.refineNumber("134914", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("67109633", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("乃𝘼𝙈๛𝙔𝙏")
end

function LOBBY() 
os.date("%G-%m-%d | TIME: %H:%M:%S") 
print("ANDA BANED KAMI SENANG??😆😆")
gg.skipRestoreState()
  gg.setVisible(true)
  os.exit()
end
while true do
  Time = os.date("%G-%m-%d | TIME: %H:%M:%S")
  if gg.isVisible(true) then
    LuaLibraryTool = 1
    gg.setVisible(false)
  end
  if LuaLibraryTool == 1 then
    HOME()
  end
end


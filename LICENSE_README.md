# 婢滆姱鎱ф櫤 路 鏅鸿兘鎷涜仒鏅鸿兘浣?License 閰嶇疆

## 绠€浠?鏈郴缁熶娇鐢?OpenClaw 鍐呯疆鐨?License 鏈哄埗杩涜鏅鸿兘浣撳垎鍙戜繚鎶ゃ€?License 鏂囦欢缁戝畾瀹㈡埛鏈哄櫒鐮侊紝瀹炵幇闃茶浆鍙戙€佹湁鏁堟湡鎺у埗銆?
## 鐩綍璇存槑

```
recruitment-agent/
鈹溾攢鈹€ SKILL.md              # 涓绘櫤鑳戒綋瀹氫箟锛堝凡绛惧悕锛?鈹溾攢鈹€ skill-1/ ~ skill-5/  # 瀛愭ā鍧?鈹溾攢鈹€ .license/             # License 閰嶇疆鐩綍锛堜粨搴撲腑涓烘ā鏉匡級
鈹?  鈹溾攢鈹€ license.sample    # License 绀轰緥鏂囦欢
鈹?  鈹斺攢鈹€ gen_license.ps1   # License 鐢熸垚鑴氭湰锛堢鐞嗗憳浣跨敤锛?鈹斺攢鈹€ .gitignore            # 蹇界暐瀹㈡埛License鏂囦欢
```

## 浣跨敤鏂规硶

### 1. 绠＄悊鍛橈細涓哄鎴风敓鎴怢icense

```powershell
# 1. 鑾峰彇瀹㈡埛鏈哄櫒鐮?瀹㈡埛杩愯: wmic csproduct get uuid

# 2. 鐢熸垚License鏂囦欢
.\license\gen_license.ps1 -MachineCode "瀹㈡埛鏈哄櫒鐮? -ExpireDays 7 -OutputFile "瀹㈡埛鍚?license"
```

### 2. 瀹㈡埛锛氬畨瑁匧icense

灏嗘敹鍒扮殑 `.license` 鏂囦欢鏀惧叆 `recruitment-agent/` 鐩綍锛孫penClaw 鑷姩璇嗗埆骞惰В瀵?SKILL.md銆?
## License 鏍煎紡璇存槑

```
# 婢滆姱鎱ф櫤 License 鏂囦欢
# 璇峰嬁淇敼鏈枃浠跺唴瀹?
[MachineCode]
xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx

[Expires]
2026-05-05

[Signature]
<hmac-sha256 signature>
```

## 瀹夊叏娉ㄦ剰浜嬮」

1. **License 鏂囦欢涓庢満鍣ㄧ爜涓€涓€缁戝畾**锛屾洿鎹㈢數鑴戦渶閲嶆柊鐢熸垚
2. **鍒版湡鍚庨渶缁垂缁湡**锛岃繃鏈?License 鏃犳硶浣跨敤
3. **涓ョ鍏变韩 License 鏂囦欢**锛屼竴缁忓彂鐜版案涔呭皝绂?4. 浠撳簱绠＄悊鍛樺簲濡ュ杽淇濈 License 鐢熸垚宸ュ叿锛屼笉寰楁硠闇?
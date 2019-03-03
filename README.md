# 바라미 프린터 OS

이 저장소는 바라미에 놓인 CR-10S를 관리하기 위해 작성된 저장소입니다.

참고자료는 다음과 같습니다.
- Creality3d CR-10S : [펌웨어](https://www.creality3d.cn/download/firmware_c0001/2.html)
- Marlin Firmware [1.1.9](https://github.com/MarlinFirmware/Marlin/archive/1.1.x.zip) + [Bugfix](https://github.com/MarlinFirmware/Marlin/archive/bugfix-1.1.x.zip)

## Recent Changes
- Bugfix 적용 완료                                              ...complete
- Manual leveling                                             ...complete
- config는 Marlin 내에 있는 정보로 진행                             ...complete
- 설정된 모터 드라이버는 X,Y = TMC2208_STANDALONE, Z,Z1,E0,E1 = A4988로 설정                                                    ...complete
- MOTHERBOARD = mks gen l 1.0으로 설정
- Filament Change 메뉴 구현                                     ...테스트 필요(일단 켜둠)
- Filament Change 호환(X+에 꽂으면 됨.)                           ...complete

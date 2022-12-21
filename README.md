# st_tooling04
readme

contains cubemx and stm32cubeide

Split

cd cubemx
split -b 40M   en.stm32cubemx-lin_v6-7-0.zip  cubemx-

Concatinate
cat cubemx-* > en.stm32cubemx-lin_v6-7-0.zip
               
Split

cd cubeide
split -b 40M    en.st-stm32cubeide_1.11.0_13638_20221122_1308_amd64.deb_bundle.sh.zip  cubeide-                

Concatinate
cat cubeide-* > en.st-stm32cubeide_1.11.0_13638_20221122_1308_amd64.deb_bundle.sh.zip



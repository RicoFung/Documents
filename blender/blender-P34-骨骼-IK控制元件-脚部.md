# P34

## 创建反向关节元件控制脚部

###### Step1. 创建新关节：(EditMode)(左脚为例)，左脚底部创建三根反向关节(样子见P34)，各自重命名

###### Step2. 转移IK控制：切换至【Edit Mode】，选中lowerLegIK_L + footControl_L关节，按 CTRL+P 选 【Keep Offset】，记得取消lowerLegIK_R亲属关系(ALT+P)，切换至【Pose Mode】，选中footMaster_L测试

###### Step3. 让关节 *Control_L 控制关节 （后脚掌）*_L：切换至【Pose Mode】，选中 *Control_L 再选中 *_L (即：先选控制者再选被控制者)，点击【Pose】->【Contraints】->【Add(With Targets)】->【Track To】，此时被控制者会变成绿色

###### Step4. 前脚掌同上

###### Step5. 切换【Edit Mode】，全选整个元件，调整位置与原脚掌重合

###### Step6. 切换【Edit Mode】，右脚同理（直接 SHIFT+D 复制）

###### Step7. 翻转命名：切换【Edit Mode】，选中骨骼，【Armature】->【FlipNames】

# 08｜粉丝使用与跨智能体交接

## 最少只需一句话

“用水晶和植物根系做一套幻想文明，给8张图的MJ提示词。”

智能体自行补齐风格卡、资产类别、光色和景别，按默认交付。用户无需知道原作者、不需要先提交复杂表格、不必具备图像工具账户才能得到提示词。

## 可复制的调用方式

- “用这个技能，做琥珀昆虫文明，8张，建筑和人物都要，16:9。”
- “参考这张图的材质和光，不复制人物，扩成城市、角色、生物和室内。”
- “换一个新风格，保留华丽材质和电影体积，别整套都是巨环。”
- “只做玻璃宗教的人物近景，3条，统一9:16。”
- “保持当前主题，补2张内部空间和2张服装细节。”
- “只提取刚才1—8的参数，不改数值。”

支持技能机制的平台加载SKILL.md及references；不支持时将入口和所需参考交给智能体读取。无统一跨平台安装路径，不声称自动适配所有平台。完整目录相对引用自包含，无私有图片或账号依赖。名称标识为fantasy-civilization-aesthetics，显示名为幻想文明美学导演；与巨物向的monumental-civilization-aesthetics并存，两者定位不同，不可互相冒充。

## 项目状态模板

下面是可填示例，使用时替换实际值，不能把示例passed当成已通过：

```yaml
project:
  topic: 琥珀昆虫文明
  output: mixed_aesthetic_series
  count: 8
  aspect_ratio: '16:9'
  medium: dimensional_cinematic_fantasy_art
  language: zh_titles_en_prompts
  model: midjourney_unspecified_version
style:
  primary_material: translucent_amber
  supporting_material: aged_brass
  contrast_materials: [dark_fabric, natural_skin, pale_stone]
  motifs: [insect_wing_veins, hive_cells, segmented_shells]
  lighting: warm_transmission_with_readable_dark_frameworks
  palette: [amber, dark_bronze, sand, restrained_blue_gray]
  exclusions: []
series:
  object_types: [architecture, city, portrait, creature, mechanism, interior, ruin, portrait]
  character_continuity_required: false
  used_compositions: []
evidence:
  images_seen: []
  prompt_sources: []
  user_preferences: []
  performance_data: not_provided
history:
  delivered_styles: []
  rejected_in_this_project: []
validation:
  text_preflight: not_yet_checked
  generated_images_inspected: false
  compatibility_verified: false
```

只记录当前项目事实。示例风格库不是已用清单，也不携带原作者私人偏好。用户要求交接时提供已用题材、成功项、待修项和真实资产引用；没有真实文件就不要编造路径。

## 角色与场景复用

若要求同角色，锁定脸部特征、发型、冠饰/服装轮廓、关键配色并使用目标工具支持的真实参考。提示词重复不能保证身份一致。若只是同一文明，不强迫所有角色同脸或同衣服。

同场景多角度时，锁定主结构、入口、通道、地平线、光向与对象相对位置。没有空间模型时说明无法严格验证未见视角，不虚构已经完成三维一致性。

## 图像到视频：只在请求时扩展

冻结美学、人物与资产→选一个相机动作→一个主要动作→环境运动→按时长组织。角色近景使用呼吸、眼神、手部和局部服饰响应；巨构使用慢视差、云影或有限机械变化。避免整张图匀速平移冒充有动作的视频。

明确材质运动：黄铜刚性、树脂甲片不随意融化、布料受风与惯性影响、玻璃折射随视角改变。不要让角色脸变形或结构无依据重组。镜头起止位置和动作阶段要与时长匹配；实际模型素材绑定格式需按平台核验。

## 原图教学卡

图像生成与教程排版分开。需要原图+提示词卡时保留真实原图，用实际排版工具放入标题、双语与参数，不生成带字假截图。未经用户要求，不自动发布、公开分享或发送给粉丝。

## 完成标准

另一智能体无需原对话即可解释美学语法，按给定对象数与画幅生成完整提示词；能自由使用人物近景与复杂仪式造型；知道何时仅提取参数；能按图像证据和文字证据分别判断；不会给读者强加原作者的拒绝项或流量结论。

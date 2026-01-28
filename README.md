# Learning Log / 学习日志

**Phase 1 — 第一阶段（最初尝试）**

### 第一部分

**中文内容**  
- **阶段目标**  
  - 探索使用AI生成可交互的智慧留言板原型，面向西北师范大学学生收集建议。  

- **工具选择与尝试方式**  
  - 使用Gemini AI网页版，未使用CLI。  
  - 尝试生成UI界面，让界面上有互动元素，如点赞按钮、公示显示、建言显示等。  

- **遇到的问题**  
  - 页面是静态的，仅显示本地代码内容，无法真正交互。  
  - 虽然界面精美，但公示需要手动更新，后台管理不方便。  
  - 初期想用Google表单关联数据，但在国内无法访问，数据无法实时展示。  
  - 考虑GitHub部署，但国内访问受限，部分功能无法使用；尝试Gitee但需提交大量个人信息而中止。  

- **阶段总结与心得**  
  - 成果：生成了视觉精美的静态原型界面，完成对交互UI的初步尝试。  
  - 问题：界面无法真正互动，数据无法同步，安全性和可访问性受限。  
  - 心得：AI能够快速生成界面和代码，但在本地与云端、交互性和安全性方面仍有局限。  

**English Translation**  
- **Stage Goals**  
  - Explore using AI to generate an interactive suggestion board prototype for students at Northwest Normal University.  

- **Tool Selection & Approach**  
  - Used Gemini AI web version without CLI.  
  - Attempted to generate a UI with interactive elements, such as like buttons, public announcement display, and suggestion submission.  

- **Challenges Encountered**  
  - The page was static, only showing local code content, without real interactivity.  
  - Although visually appealing, public announcements required manual updates, and backend management was inconvenient.  
  - Initially tried linking Google Forms for data, but inaccessible in China, so data could not be displayed in real-time.  
  - Considered deploying on GitHub, but access is restricted in China; Gitee deployment was abandoned due to excessive personal information requirements.  

- **Stage Summary & Insights**  
  - Achievements: Generated a visually appealing static prototype, completing initial attempts at interactive UI.  
  - Problems: Interface could not interact in real-time, data synchronization failed, security and accessibility were limited.  
  - Insights: AI can quickly generate interfaces and code, but local/cloud interaction, interactivity, and security remain major limitations.
<img width="1130" height="1377" alt="af9f316fefda4fe7ec51a1c0f053b15e" src="https://github.com/user-attachments/assets/19c58577-11e6-4bc3-bed2-4a0a753a640f" />

-----------------------------------------------------------------------------------------------------

**Phase 2 — 第二阶段（CLI尝试与界面优化）**

### part1/第一部分

**中文内容**  
- **阶段目标**  
  - 尝试使用CLI与网页版Gemini AI结合，优化智慧留言板的功能与界面交互。  
- **工具选择与尝试方式**  
  - 保留网页版Gemini AI作为主要助手。  
  - 在CLI中尝试进行编程，实现后台逻辑和数据处理。  
- **遇到的问题**  
  - 初步生成界面因提示词不够精确，视觉不够美观。  
  - 与Gemini AI CLI沟通需要多次转述，因为AI无法完全理解目标功能。  
  - 这种沟通方式导致操作不够便捷，需多次修正和尝试。  
- **阶段总结与心得**  
  - 成果：完成CLI与网页版AI结合的初步尝试，生成可交互界面雏形。  
  - 问题：沟通需转述多次，操作不便，交互体验仍有缺陷。  
  - 心得：这一阶段为后续界面改进和权限管理提供重要经验。  
**English**  
- **Stage Goals**  
  - Attempt to combine CLI with the Gemini AI web version to optimize the suggestion board's functionality and interface interaction.  
- **Tool Selection & Approach**  
  - Retained the Gemini AI web version as the main assistant.  
  - Attempted programming in the CLI to implement backend logic and data processing.  
- **Challenges Encountered**  
  - Initial generated interface lacked visual appeal due to imprecise prompts.  
  - Communication with Gemini AI CLI required multiple repetitions, as the AI could not fully understand the intended functions.  
  - This communication method made operations less convenient, requiring multiple corrections and retries.  
- **Stage Summary & Insights**  
  - Achievements: Completed preliminary attempts combining CLI with the web AI, generating an interactive interface prototype.  
  - Problems: Communication required multiple repetitions, operations were inconvenient, interactivity remained limited.  
  - Insights: This stage provided valuable experience for future interface improvements and permission management.

<img width="415" height="438" alt="image" src="https://github.com/user-attachments/assets/f709c23e-a760-4cfc-8337-47be554e55a9" />

<img width="415" height="577" alt="image" src="https://github.com/user-attachments/assets/8e48f48e-6191-4f50-a29a-a6c5bc2e41e8" />

----------------------------------------------------

### part2/第二部分

**中文内容**  
- **阶段目标**  
  - 改进界面美观度与交互体验，添加管理员权限管理功能。  
- **界面与功能优化**  
  - 重新设计UI界面，使页面更直观、创意，便于用户浏览和提交建言。  
  - 页面上增加隐藏管理员入口，通过双击按钮输入密码登录。  
  - 不同管理员密码对应不同权限，处理提案或文件。  
  - 审批结果会显示在公示区，用户可查看提案是否通过或被驳回。  
- **问题与挑战**  
  - 所有数据仍在本地，无法跨设备同步。  
  - 前端密码存在安全隐患，F12可查看。  
  - 缺乏后端和服务器支持，技术实现复杂。  
- **阶段总结与心得**  
  - 成果：完成界面美化、隐藏管理员入口及权限管理设计，增强交互性和功能性。  
  - 问题：本地化限制和安全性问题仍未解决。  
  - 心得：对界面设计和权限管理有了更清晰理解，为后续云端同步与安全管理提供方向。  

**English**  
- **Stage Goals**  
  - Improve interface aesthetics and interactivity, adding administrator permission management.  
- **Interface & Function Optimization**  
  - Redesigned the UI to be more intuitive and creative, facilitating browsing and submitting suggestions.  
  - Added a hidden administrator entry on the page; double-clicking the button allows password login.  
  - Different passwords correspond to different administrator permissions for handling proposals or files.  
  - Approval results are displayed publicly; users can see whether proposals are approved or rejected.  
- **Challenges Encountered**  
  - All data remained local, preventing cross-device synchronization.  
  - Frontend passwords were insecure and could be seen via F12.  
  - Lack of backend and server support made implementation complex.  
- **Stage Summary & Insights**  
  - Achievements: Completed interface beautification, hidden admin entry, and permission management design, enhancing interactivity and functionality.  
  - Problems: Localization limitations and security issues remained.  
  - Insights: Gained clearer understanding of interface design and permission management, guiding future cloud synchronization and security improvements.

https://github.com/user-attachments/assets/330cc998-ee6b-41ef-b745-c1583f19abad


-------------------------------------------------

### part3/第三部分

**中文内容**  
- **阶段目标**  
  - 尝试解决管理员权限安全、数据同步及云端管理问题，提升系统可用性。  
- **挑战与尝试**  
  - 前端隐藏入口存在安全隐患，尝试邮箱验证、验证码登录等方式提升安全性，但技术复杂。  
  - 希望实现学生提交数据、管理员端实时查看并处理，同时前端页面同步显示审批结果。  
  - 尝试多种云端方案（钉钉多维表格、金数据、leancloud、Supabase），均出现访问限制或服务停止问题。  
  - 国内工具（腾讯表单等）无法自动同步至前端，仍需手动操作。  
- **心理感受**  
  - 技术壁垒高，日志记录繁琐，AI生成的代码出现黑屏或运行错误。  
  - 多次尝试失败，出现对话中断和进度延迟，导致心态崩溃。  
  - 一度认为项目可能烂尾，情绪上受到打击。  
- **阶段总结与心得**  
  - 成果：明确了云端同步和管理员权限管理关键难点。  
  - 问题：AI能生成代码，但技术理解和个人能力仍不可替代。  
  - 心得：经验为后续寻找可行替代方案奠定基础，同时锻炼耐心和问题解决能力。  

**English**  
- **Stage Goals**  
  - Attempt to solve administrator permission security, data synchronization, and cloud management to improve system usability.  
- **Challenges & Attempts**  
  - Frontend hidden entry had security risks; attempted email verification and code login, but technically complex.  
  - Aimed to allow student submissions, real-time admin review, and frontend display of approval results.  
  - Tried various cloud solutions (DingTalk multidimensional spreadsheet, Jinshuju, LeanCloud, Supabase), but faced access restrictions or discontinued services.  
  - Domestic tools (Tencent Forms, etc.) could not automatically sync to the frontend, requiring manual handling.  
- **Psychological Experience**  
  - High technical barriers, cumbersome log recording, AI-generated code showed black screens or errors.  
  - Multiple failed attempts, interrupted dialogues, and delayed progress led to mental collapse.  
  - Momentarily felt the project might be abandoned, causing emotional distress.  
- **Stage Summary & Insights**  
  - Achievements: Identified key challenges in cloud synchronization and admin permission management.  
  - Problems: AI can generate code, but technical understanding and personal capability remain irreplaceable.  
  - Insights: Experience laid the foundation for future feasible solutions and cultivated patience and problem-solving skills.

![a25497a59ecb430deefaebb07290eca4](https://github.com/user-attachments/assets/72a85855-ba89-4f4c-82e0-6c74b0f42c19)
![a4b7c8e911811a200b45881ae8b8b7d5](https://github.com/user-attachments/assets/c9fbf412-950c-4b5b-8893-cf59e48cff60)

----------------------------------------------------------------------------------------------------------------------
**Phase 3 — 第三阶段（国内雏形设计）**

{**中文内容**  
- **阶段目标**  
  - 在国内环境下搭建智慧留言板的逻辑雏形。  
  - 确保学生能够顺利提交建言，管理员能够审核和分类，同时前端页面展示审批结果。  
- **工具选择与界面设计**  
  - 考虑到GitHub在国内访问受限，项目暂未迁移，而是先在本地和国内工具环境下完成逻辑设计。  
  - 使用腾讯表单收集学生建言，保证国内学生能够填写问卷，并通过微信登录或腾讯账号登录，提高安全性和可操作性。  
  - 对前端界面进行重新设计，增加跳转表单按钮，让学生可以直接访问问卷。  
- **数据处理与同步逻辑**  
  - 学生提交的数据最终会同步到智慧表格，由管理员审核和分类处理。  
  - 由于经过尝试腾讯表单无法直接与前端公示同步，逻辑上设想通过人工将审核通过的数据整理到谷歌表格，再更新前端页面显示公式信息。  
  - 目标是实现学生端提交、管理员端处理、前端实时公示的完整流程。  
- **分类与公示**  
  - 建立分类模块，如生活权益、教学教务等，便于学生浏览和提交建言。  
  - 审批通过的提案显示在公示区，驳回的提案不显示。  
  - 用户可查看历史提案，避免重复建言。  
- **阶段收获与心得**  
  - 搭建了国内可行的逻辑雏形，验证了数据收集、分类管理、公示流程的可操作性。  
  - 考虑了安全性和交互体验，理论上保证方案可行。  
  - 第二阶段的试错经验让逻辑更成熟，界面思路更清晰。  
  - AI在辅助生成界面和代码中仍发挥重要作用，但个人的技术理解和掌握能力仍不可替代。  
  - 在工具受限、国内访问受限的情况下，仍完成了可行的逻辑设计，保证项目不会烂尾。  

**English**  
- **Stage Goals**  
  - Build a logic prototype of the interactive suggestion board suitable for domestic use.  
  - Ensure students can submit suggestions, admins can review and categorize them, and the front-end displays approval results.  
- **Tool Selection & Interface Design**  
  - Considering GitHub access restrictions in China, the project was not migrated yet; focus was on local and domestic tool environment for logic design.  
  - Used Tencent Forms for student submissions, allowing login via WeChat or Tencent account to improve security and usability.  
  - Redesigned front-end interface, added a button to redirect to the form, enabling students to directly access the survey.  
- **Data Handling & Synchronization Logic**  
  - Submitted student data is intended to sync to a smart spreadsheet for admin review and categorization.  
  - Due to Tencent Forms limitations, automatic synchronization with the front-end is not possible; manually approved data can be transferred to Google Sheets to update the front-end formulas.  
  - Goal: achieve a full workflow where students submit, admins process, and the front-end displays results in real time.  
- **Categorization & Public Display**  
  - Created categories such as life rights, academic affairs, etc., for easier browsing and submission.  
  - Approved suggestions are displayed on the public board; rejected suggestions are not shown.  
  - Users can view historical submissions to avoid duplication.  
- **Stage Insights & Reflections**  
  - Built a feasible domestic logic prototype, validating data collection, categorization, and public display workflow.  
  - Considered security and interaction, making the solution theoretically workable.  
  - Lessons from Phase 2’s trial-and-error made the logic more mature and interface design clearer.  
  - AI played a key role in generating interfaces and code, but personal technical understanding is still indispensable.  
  - Despite tool and access limitations, a practical logic prototype was completed, ensuring the project would not be abandoned:)}
 ![7a224737652e61e61e297be7ffa3efcd](https://github.com/user-attachments/assets/0c003fd6-29e8-4a4f-ac50-e8082deda971)
![520ffffbbe407a85afcded3cbe69c27a](https://github.com/user-attachments/assets/c61adf71-201d-4f4f-87fe-638e4912ff35)


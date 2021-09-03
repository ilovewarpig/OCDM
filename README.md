# OCDM
Online learner cognitive disequilibrium modeling and recognition based on resource access sequence
<br/>
本研究依托 "STEM College 云课堂"教学平台，教学人员将教学内容以微课的形式上传到云平台，学生可以通过计算机、手机、平板等工具异步学习。该研究的参与者是由79名参加《手把手体验Python与机器学习》课程的教育技术系二年级本科生组成。该课程由11个单元组成，教学内容以视频、练习和外部链接为载体，包含69个学习视频、55个随堂练习和9次讨论区活动。完成练习后，学生可以选择将自己的答案和标准答案进行比较，自行报告比较后的结果（好于标准答案、和标准答案一样、接近标准答案、与标准答案不同和以上都不是），系统将最后一次报告记录作为比较结果，并记录最新的时间戳。该记录不会影响学生的考评成绩，但是作为认知冲突的标签。<br/>

学习者于在线平台中产生的日志数据存储于在线学习系统的服务器中，包括学习者基本信息和学习过程中的点击流数据，例如对各类学习资源的访问时间戳、持续时间等。79名学习者在一个学期中共产生了20851条学习记录。<br/><br/>

这些数据已经脱敏并开放，包括全体学习者的日志数据(course_log_data_anonymization.csv)、学习者自我报告记录(self_report_data.csv)、课程大纲(syllabus.csv)、持续型学习者在第2单元的日志数据(Unit2_Cluster1_log.csv)和策略型学习者在第2单元的日志数据（Unit2_Cluster2_log.csv）
此外，我们也提供了用于预测模型的数据集(resource_access_seq_dataset.csv)和360个预测学习者认知冲突的建模结果(model_result_cv5.csv)

# FPGABasedHighPerformanceTargetChecking
it is a set for all the respository of the project.

这个项目由4个人完成，分别是[linxiaobo110](https://github.com/linxiaobo110)，[hahahaxyf](https://github.com/hahahaxyf)，[Yang Liu](https://github.com/liuyang151617)， 和 [liuyanglinlyl](https://github.com/liuyanglinlyl)完成。
。项目分由3部分组成，分别是是platform（平台）、algorithm（算法）、application（应用），这三个部分以submodule的形式链接在本仓库中。

- 平台部分主要由liuyanglinlyl负责，主要包含用vivado设计包含dpu的boarddesign，以及petalinux如何使用vivado生成的hdf和bit文件定制os。
- 算法部分主要由Yang Liu负责，主要包含使用dnndk for x86将已有深度模型的压缩和转换成fpga可以运行的模型。
- 应用部分主要由分别是hahahaxyf负责，主要使用dnndk for ultra96调度生成的压缩模型，以及摄像头、图像读取、图像保存等。
- 此外presentation这个目录用来放我们的项目计划书、总结报告、相关视频。

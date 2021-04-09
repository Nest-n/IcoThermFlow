# IcoThermFlow
Resolução de sistema de equações diferenciais aplicando o método de Elementos Finitos à fenômenos de transportes para problemas de escoamentos incompressíveis com transferência de calor

O programa foi desenvolvido aplicando uma programação orientada à objetos, juntamente a aplicação de um paralelismo local e homogênio no CPU. Para validação do código foi
submetido ao escoamento da Cavidade com tampa deslizante (Lid-Driven Cavity) para Reynolds 100, 400 e 1000 para diversas malhas homogêneas e estruturadas. O mesmo é acoplado com o BlockMesh do OpenFOAM para geração de malha e para pós-processamento é utilizado o ParaView.

# Dimension_chain
Рассчёт технологических размерных цепей в помощь инженеру. Solving technological dimension chains for ingeneers
Использован WPF, MVC. Размерные цепи представлены в виде графа, в котором вершины - это поверхности детали, 
дуги - это связывающие их размеры. Поиск замыкающего звена в размерной цепи (конструкторского размера с допусками или припуска)
осуществляется путём поиска кратчайшего пути между вершинами на графе по технологическим дугам.
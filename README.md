Здесь на реальных датасетах и на искусственных матрицах сравниваются два способа композиционного анализа: t-test и scCODA.

Из теста на mock-матрицах следует:

t-test неспособен учитывать композиционный эффект, в отличие от scCODA; 

оба теста достаточно робастны, чтобы работать с небольшим количеством выбросов;

t-test оказался чувствительнее scCODA в случае малых популяций клеток.

Помимо этого стоит отметить, что время проведения scCODA значительно выше, чем для t-test, из-за 20000 итераций сэмплирования при MCMC. 

Самые актуальные колабы - по ссылке:

волчанка: https://colab.research.google.com/drive/1YLKckBgEAO9CUnIfEd9XC3hjV2iAL0Hk?usp=sharing

ревматоидный артрит: https://colab.research.google.com/drive/1a70jyyQnC524wFToLrEiy0ZYIC3tdCMj?usp=sharing

искусственные данные: https://colab.research.google.com/drive/1MoKQnPXZFzbPasLw49MkWoVnJ_X13Ygu?usp=sharing

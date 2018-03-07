
# eXtreme MultiLabel (XML) Classification

Une tâche de classification est dite "extrême" dès lors que le nombre de classes considérées devient très important (de quelques dizaines à plusieurs millions). L'appellation "Multilabel" désigne quant à elle une classification où chaque échantillon ("sample") peut avoir plus d'une catégorie ; tous les échantillons ne sont d'ailleurs pas nécessairement associés au même nombre de catégories.

Dans ce notebook, nous allons montrer pourquoi ce problème ne peut pas être raisonnablement approché de façon naïve, puis justifier et mettre en place une méthode basée sur l'article [**Deep Extreme Multi-label Learning**](https://arxiv.org/pdf/1704.03718.pdf) par Zhang et al.


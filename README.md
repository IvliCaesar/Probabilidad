# Probabilidad

Course material in probability by César Galindo: sixteen Jupyter notebooks (in Spanish), lecture
notes, exercise sets and slides. The notebooks go from the classical (Laplace) model to simulation,
limit theorems, Gaussian vectors and a set of classical problems, each mixing definitions, proofs
and Python code that checks them.

## Notebooks

The notebooks are meant to be read in order. Each one runs top to bottom with a fixed seed.

| # | Notebook | Topics |
|---|---|---|
| 01 | [Probabilidad clásica](cuadernos/01_Probabilidad_Clasica.ipynb) | Laplace model with Python sets, law of the sum of two dice, conditional probability, independence, relative frequencies |
| 02 | [Cálculo de probabilidades](cuadernos/02_Calculo_de_Probabilidades.ipynb) | events as sets and predicates, a `DistProb` class, the Newton–Pepys problem |
| 03 | [Urnas](cuadernos/03_Urnas.ipynb) | the four ways to draw (ordered or not, with or without replacement), hypergeometric vs. binomial, multinomial, exchangeability, Bayes with two urns, Pólya's urn, interactive urn lab |
| 04 | [Ejercicios de probabilidad clásica](cuadernos/04_Ejercicios_Probabilidad_Clasica.ipynb) | Venn diagrams, repeated throws, a two-player dice game, sum of three dice |
| 05 | [Condicional e independencia](cuadernos/05_Condicional_e_Independencia_Ejercicios.ipynb) | solved exercises with counterexamples checked in code |
| 06 | [El módulo `random`](cuadernos/06_Modulo_Random.ipynb) | pseudo-random generators, seeds, permutations, frequentist vs. classical coin tosses |
| 07 | [Frecuencia y distribución](cuadernos/07_Frecuencia_y_Distribucion.ipynb) | empirical frequencies, expectation and variance of the sum of two dice |
| 08 | [Muestreo con NumPy](cuadernos/08_Muestreo_con_NumPy.ipynb) | `default_rng`, Bernoulli trials, binomial law, sample means, Galton board |
| 09 | [Transformada inversa](cuadernos/09_Transformada_Inversa.ipynb) | distribution functions (discrete, continuous, Cantor, mixed), generalized inverse, sampling, histograms, Q–Q plots |
| 10 | [Simulación y teoremas de aproximación](cuadernos/10_Simulacion_y_Teoremas_de_Aproximacion.ipynb) | Cauchy, binomial–Poisson, memorylessness, geometric–exponential, four geometric samplers |
| 11 | [La distribución normal](cuadernos/11_Distribucion_Normal.ipynb) | density, standardization, De Moivre–Laplace with continuity correction, diversification risk, MLE |
| 12 | [La media muestral](cuadernos/12_Distribucion_de_la_Media_Muestral.ipynb) | standard error, sample size, central limit theorem for skewed populations |
| 13 | [Box–Muller y normal bivariada](cuadernos/13_Box_Muller_y_Normal_Bivariada.ipynb) | Box–Muller, Gaussian vectors via Cholesky, principal axes, singular covariances, linear change of variables |
| 14 | [Gaussiana multivariada](cuadernos/14_Gaussiana_Multivariada.ipynb) | multivariate density, 3D samples, maximum likelihood |
| 15 | [Ruina del jugador](cuadernos/15_Ruina_del_Jugador.ipynb) | ruin probability and expected duration, vectorized simulation, nearly fair games |
| 16 | [Problemas clásicos](cuadernos/16_Problemas_Clasicos.ipynb) | De Méré, birthday paradox, Monty Hall, Bertrand's box, three prisoners, matching problem and random permutations, coupon collector, Buffon's needle, with proofs and an object-oriented design |

Notebooks 03, 10, 11 and 15 contain interactive Altair charts, and notebook 03 has an
`ipywidgets` urn lab. GitHub's preview shows them as static output; open the notebooks in
Jupyter, VS Code or Colab, or on [nbviewer](https://nbviewer.org/github/IvliCaesar/Probabilidad/tree/main/cuadernos/),
to use the sliders.

### Running

```bash
pip install -r requirements.txt
jupyter lab cuadernos/
```

## Notes

| File | Content |
|---|---|
| [Probabilidad_y_Medida](notas/Probabilidad_y_Medida.pdf), [beamer](notas/Probabilidad_y_Medida_Beamer.pdf) | measure theory from length on ℝ to the Lebesgue integral, read as probability |
| [Cambio_de_Medida](notas/Cambio_de_Medida.pdf) | Radon–Nikodym, density processes, martingales and change of measure in stochastic analysis |
| [Fonctions_Caracteristiques](notas/Fonctions_Caracteristiques.pdf) | characteristic functions (in French) |
| [Sucesiones_de_Variables_Aleatorias 1](notas/Sucesiones_de_Variables_Aleatorias_1.pdf), [2](notas/Sucesiones_de_Variables_Aleatorias_2.pdf), [3](notas/Sucesiones_de_Variables_Aleatorias_3.pdf), [solutions](notas/Sucesiones_Soluciones.pdf) | modes of convergence of random variables |
| [TCL_Notas](notas/TCL_Notas.pdf) and parts [1](notas/TCL_1_Convergencia_Debil.pdf), [2](notas/TCL_2_Continuidad_de_Levy.pdf), [3](notas/TCL_3_Demostracion.pdf), [4](notas/TCL_4_LGN_Lindeberg_Lyapunov.pdf) | central limit theorem: weak convergence, Lévy continuity, proof, strong law, Lindeberg–Feller and Lyapunov |
| [Cadenas_de_Markov](notas/Cadenas_de_Markov.pdf), [beamer](notas/Cadenas_de_Markov_Beamer.pdf) | finite Markov chains in discrete time |
| [Estadistica_Inferencial](notas/Estadistica_Inferencial.pdf) (with [source](notas/Estadistica_Inferencial.tex), XeLaTeX) | classical statistical inference: point estimation and maximum likelihood, confidence intervals from pivots, the CLT, $t$ and $\chi^2$, hypothesis tests and Neyman–Pearson, least squares and Gauss–Markov, with solved exercises, several from finance |

## Exercises

- [Ejercicios_CFA_Probabilidad](ejercicios/Ejercicios_CFA_Probabilidad.pdf) (with [source](ejercicios/Ejercicios_CFA_Probabilidad.tex)): probability exercises in the style of the CFA exam.
- [Guia_Estudio_Probabilidad](ejercicios/Guia_Estudio_Probabilidad.pdf): study guide for a final exam in probability and descriptive statistics, with step-by-step solutions.

## Slides

- [Lenguaje_Probabilistico](diapositivas/Lenguaje_Probabilistico.pdf): Anglicisms, Gallicisms and the languages of probabilistic computation: notation, symbols, pseudocode and C.

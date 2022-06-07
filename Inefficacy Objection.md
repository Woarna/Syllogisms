# Inefficacy Objection towards Veganism

An **inefficacy objection** says, in one way or another, that veganism will have no impact on the goals of the vegan. This seems very dubious. On p.26, ![[MCMAIOv2-3 (1) 1.pdf|this article]] says:

"The actual probability of being on a threshold is probably not relevant to the ethical evaluation of meat purchasing, but it can be estimated using some basic knowledge of current industry practice. In the poultry industry, the large 'growers' of 'broiler' chickens produce, on average, 329,000 chickens per year (The Pew Environment Group 2013b). If the finest adjustment that a chicken distributor can make is to delay a shipment of birds to the grower by one day, then that means the threshold size will be one day’s worth of birds for one farm. This number comes out close to 900 birds. As a result, it is likely that a consumer, when choosing to buy a chicken, has close to a $\frac{1}{900}$ chance of being on the threshold, & if a consumer decision triggers the threshold event, the impact will be that 900 fewer chickens will be sold that year." 

That’s a $\frac{1}{900}$ chance of triggering the threshold **per purchase**. The average consumer purchases 30 chickens per year. We can calculate the probability $(P)$ of triggering the threshold in one year **at least** once with the binomial distribution formula:

| Action                                                    | **$P$** Of Tripping Threshold **$1+$** Times In 1 Year                                  | **$P$** Of Tripping Threshold **$1+$** Times In 75 Years                                          |
| --------------------------------------------------------- | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| Buying 30 chickens/year (the average consumer).           | $\begin{flalign*}P(x \geq 1) & = 1-(1-\frac{1}{900})^{30}\\& = 3.2\%\end{flalign*}$     | $\begin{flalign*}P(x \geq 1) & = 1 - (1-\frac{1}{900})^{(30 \cdot 75)}\\& = 91.8\%\end{flalign*}$ |
| Buying $\frac{1}{2}$ the average amount of chickens/year. | $\begin{flalign*}P(x \geq 1) & = 1 - (1-\frac{1}{900})^{15}\\& = 1.6\%\end{flalign*}$   | $\begin{flalign*}P(x \geq 1) & = 1 - (1-\frac{1}{900})^{(15 \cdot 75)}\\& = 71\%\end{flalign*}$   |
| Buying $\frac{1}{3}$ the average amount of chickens/year. | $\begin{flalign*}P(x \geq 1) & = 1 - (1-\frac{1}{900})^{10}\\& = 1.1\%\end{flalign*}$   | $\begin{flalign*}P(x \geq 1) & = 1 - (1-\frac{1}{900})^{(10 \cdot 75)}\\& = 56\%\end{flalign*}$   |
| Buying $\frac{1}{4}$ the average amount of chickens/year. | $\begin{flalign*}P(x \geq 1) & = 1 - (1-\frac{1}{900})^{7.5}\\& = 0.83\%\end{flalign*}$ | $\begin{flalign*}P(x \geq 1) & = 1 - (1-\frac{1}{900})^{(7.5 \cdot 75)}\\& = 46\%\end{flalign*}$  |
                                                                                                                                                             
Even for low consumers, there is a considerable chance of triggering the threshold over a lifetime. #ethics #math #philosophy #veganism

Courtesy of Ask Yourself and Avi
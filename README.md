# An Inquiry into the Differential Impacts Across States of Gun-Control Legislations following the 2018 Parkland High School Shooting

Arthur Langlois, 
Northeastern University


In February 2018, an armed man opened fire at the Marjory Stoneman Douglas High School in Parkland, Florida, killing 17 people and injuring 15 others. This act of violence was one of the 3,428 shootings that occurred in the US since 2014 (Gun Violence Archive, 2022), or, in other words, one of the daily shootings occurring for 7 years straight in the country. The 2018 Parkland school shooting has sparked debates over the broader issue of gun violence, rather than uniquely regarding school shootings, or mass shootings. As highlighted by various policy makers and activists, gun violence is not limited to mass shootings: they also account for suicides, and less than four casualties’ homicides (Figure 1). Following this horrific act of terror, an unusual thing happened: State legislators implemented various legislations to restrict gun access, pressured by various movements led by survivors of the massacre. While the specificities of the legislations passed are rather heterogenous, they all shared a common motive: restrict gun access in an attempt to limit the number of gun violence, and more specifically mass shootings in their respective states. Across the country, about half of the states passed at least one legislation aiming to restrict gun access. Yet unsurprisingly, the distribution by political affiliation of newly passed legislations was disparate, with 44 democrats-controlled-states tightening restrictions, compared to 20 republican controlled-states tightening restrictions (9 republican states lowered their gun laws restrictions). These various laws being passed across the country were unequivocally seen as a victory for gun control advocates, even considered as a legislative “tectonic shift” by the Giffords Center To Prevent Gun Violence. 

The goal of this empirical project is to 1- Measure to extent to which the gun-restricting policies implemented following the 2018 Parkland shooting were successful in reducing gun violence across states. 2- Examine the cross states differences in the effectiveness of their respective policies, to identify which policies seem to be most efficient in reducing gun violence. 
We will focus on States that have both implemented policies in response to 2018’s Parkland shooting, and historically have high number of mass shootings, in an attempt to understand the impact of the policies where mass shootings are most problematic. These states include: California, Florida, Washington, Wisconsin, New York, Ohio and Illinois (Table 1). Even though these states share comparable legislations such as domestic violence restrictions and urban gun violence reduction programs, they are different in nature, therefore we will provide a thorough description of each state’s newly implemented legislative framework since 2018. The dataset is comprised of daily city level data on gun incident with number of casualties and injuries between 2014 and 2021, compiled by the Gun Violence Archive, as well as daily suicide rates at the state level since 1999 obtained from the CDC. These two datasets will be aggregated at the state and monthly level to construct a novel database. We will follow a synthetic control methodology in order to estimate the causal impact of the policies on the number of gun related incidents. 


According to the CDC, there are about 45,000 annual deaths linked to gun violence in the country, and according to a common study by the Healthcare Cost and Utilization Project, the CDC and Everytown Research, the yearly economic cost of gun violence is estimated at $280 billion dollars (with $3.5 billion of medical costs alone, and an estimated 214.2 billion loss in “intangible loss of victims and survivors due to either a life cut short or a person permanently disabled by gun violence”). These economic costs vary highly depending on states, with southern states being hit the most (Figure 2). More specifically, gun violence has been shown to have significant sociological and psychological detrimental impacts, most notably on children, community wellbeing, and often on multiple generations (Cook & Ludwig, 2002, Soni & Tekin, 2020, and Dursun, 2019). Gun violence is largely perceived as one of the largest problem in the country, with 72% of the population thinking of it as either a “Very Big Problem” or a “Moderately Big Problem”. On the other hand, gun violence regulation has also become a divisive political subject: according to the same survey by the Pew Research Center, 80% of self-identified democrats respondents considered that gun laws ought to be stricter than they are today, compared with 20% for self-identified republicans (Pew Research Center, 2021, see Figure 3). 

The combination of high societal costs of gun violence along with the importance place it has taken in political debate calls for the need of rigorous assessment of policies effectiveness aiming at reducing gun violence. We hope the results of this research can provide guidance to policymakers and the general public at large regarding the effectiveness of these crucial policies. 

#Literature review

At its most fundamental level, the economic ethos with regards to gun control is based on the basic notion of externalities; for Chaudhri and Geanakoplos, gun owners can be divided into three categories: hunting and sporting related, individual safety, and criminal activity (Chaudhri & Geanakoplos, 1998). In the situation where gun availability is widespread in a nation, renders an increased number of potential criminals now armed with guns. The theoretical consequence is therefore a heightened number of criminal activity, yielding justification for regulations (Cook et al). Because the results of guns misuse are costly/difficult to limit and sanction, Cook et al. find a “logical case for regulations designed to preempt criminal use to facilitate law-enforcements efforts, to limit the likelihood of accidental misfires and achieve other public purposes”, with the latter referring to ex ante regulation by S. Shavell (Shavell, 1984 & 2004). A short theoretical paper by Chaudhri and Geanakoplos raised a theoretical model, showing that all things held equal, due to the elastic nature, rendering guns illegal would greatly reduce their demand. (Chaudhri & Geanakoplos, 1998).


Urban Gun Violence Reduction Programs: There are a wide array of gun violence reduction programs, and significantly vary across jurisdictions. Most models employ either through street outreach, (which its implementation was associated with a 50% decline in gun injuries, as well as a 63% decline in shooting victimization <link>) Group Violence Intervention Programs (GVI), or Hospital-Based Violence Intervention Programs (HVIPs). These different types of models have been shown to significantly reduce gun violence in targeted neighborhoods, as emphasized by a report by Everytown Research. These models are often used in opposition to the myth that most gun violence related crimes are gang-related. According to the report, “In reality, although some gun violence is connected to gang activity, gun violence occurs more frequently within informal social networks tied together by the places people live, the schools they attend, and their places of worship. Gun violence within these social networks is further concentrated into a very small percentage of people. This gun violence frequently occurs spontaneously, following a dispute or perceived disrespect, and between people who are known to one other. These encounters become deadly because a gun is present”. (Everytown Research & Policy, 2021).

Domestic Violence Restrictions: Zeoli et al. show that prohibiting gun ownership from individual with a history of domestic violence has shown significant reduction on intimate partner homicides (about 10% reduction), across the country (Zeoli et al, 2018). This was motivated by previous research done by Zeoli et al., proving that out of 89 mass shooters between 2014 and 2017, 28 were suspected of domestic violence with 61% had been accused or convicted for domestic violence (Zeoli & Paruk, 2020)

Ownership restrictions: The academic literature is largely divided on the question of the impacts of ownership restrictions posited that gun ownership rates are strong predictors of homicide rates at the state level (Gius, 2009). In a 1993 article, Kleck and Patterson found on the opposite, that most gun control restrictions in large cities have no significant effects on violence rates (Kleck, & Patterson, 1993)

Expanded background checks: In a 2017 study, Miller showed that 22% of current gun owners had acquired their firearm in the past two years, did so without any background check (Miller et al., 2017). Using longitudinal data at the state level between 1996-2005, Sen showed that more extensive background checks prior gun purchase are associated with both a decrease in firearm homicide and suicidal deaths (Sen & Panjamapirom, 2012). 

Bump-Stock Ban: Bumps stocks are attachment made to a semiautomatic rifle enabling it to fire faster, and be used similarly than an automatic rifle. This issue came to the attention of policy-makers and the public when it was discovered that twelve of the rifles the Las Vegas mass murder used in his 2017 attack had been adjusted by a bump stock. Following this tragic event, even most firearms advocates such as the National Rifle Association expressed their support for tighter restrictions on such devices. A study in 2018 showed that 81% of American voters supported a ban on bump stocks (New York Times, 2017). In a firearms regulation’s experts survey led by the NYT, a ban on bump stock, and more broadly on semi-automatic and automatic firearms reached a mean score of 6.1/10, when asked about how effective its implementation would be in preventing gun deaths. 

Red Flag Laws: Extreme Risk Protection orders, or “Red Flag Laws” are a set of legislation allowing a judge to temporarily remove a person’s access to firearms when presented with evidence that are posing a risk for either others or themselves. The psychiatric literature has consistently shown that the implementation of ERPOs has saved lives (Swanson, 2019) as supported by state-wide comparative research in Indiana and Connecticut by Kivisto in 2018 (Kivisto et al., 2018). While the specificities of the laws differed across the two states, the results were the same: ERPOs are associated with a diminished number of gun related deaths, with most notable results regarding suicides (7.5% reduction in firearm suicides in the ten years following its enactment). 

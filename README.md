# InterviewSelectionPrediction

I am in college and I need to know which skills on my resume will gurantee me an Interview, sound's great right?
So I tried to correctly predict that will my resume be selected for interview If I have some particular skills.

### Factors Affecting Selection
Along with skills there were some other features in data which can affect the selection.
1. Veteran: 1 if the applicant is a veteran, 0 otherwise
2. Female: 1 if the applicant is female, 0 otherwise
3. URM: 1 if the applicant is an underrepresented minority, 0 otherwise
4. Disability: 1 if the applicant has a disability, 0 otherwise

All these factors can affect the selection of a candidate

### Performance of Various Algorithms

1. Comparision of accuracy with only gender feature and all the skills features

![Gender Plot](plotGender.png)

2. Comparision of accuracy with only Veteran status feature and all the skills features

![Veteran Plot](plotVeteran.png)

3. Comparision of accuracy with all the features 

![All Plot](plotAll.png)

4. Comparision of accuracy with only skills features

![Skills Plot](plotSkills.png)

Now I don't want that Machine reject an application on the basis of Gender, Disability, minority status or veteran status. Let's keep that control in the hands of HR.

### Picking up correct Model

So we select the model which have highest accuracy with only skills features and that is Kernel SVM with RBF kernel


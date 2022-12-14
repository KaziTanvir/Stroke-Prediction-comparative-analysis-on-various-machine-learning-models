# Stroke Prediction comparative analysis on various machine learning models
<br>
## What is a Stroke?

A stroke, sometimes called a brain attack, occurs when something blocks blood supply to part of the brain or when a blood vessel in the brain bursts. In either case, parts of the brain become damaged or die. A stroke can cause lasting brain damage, long-term disability, or even death. <br>

## Why we need stroke prediction analysis?

This delay is particularly concerning when we consider that Ischemic stroke patients suffer the loss of two million brain cells every minute until blood flow is restored. In this context, an earlier diagnosis can mean faster treatment, with one Harvard Medical study breaking down the benefits as follows: <br>

“For every 15-minute acceleration of time to…treatment, found: <br>

<ul>
    <li>4% lower risk of in-hospital death </li>
    <li>4% better odds of walking independently after leaving the hospital </li>
    <li>3% better odds of being sent home instead of to an institution </li>
    <li>4% lower odds of a brain hemorrhage.” </li>
    
</ul>

<br>

## Models Used:

<ul>
    <li>Gaussian Naive Bayes : <p>Naive Bayes methods are a set of supervised learning algorithms
based on applying Bayes’ theorem with the “naive” assumption of
conditional independence between every pair of features given the
value of the class variable. Bayes’ theorem states the following
relationship, given class variable <span class="math notranslate nohighlight"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" tabindex="0" ctxtmenu_counter="0" style="font-size: 113.1%; position: relative;"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D466 TEX-I"></mjx-c></mjx-mi></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>y</mi></math></mjx-assistive-mml></mjx-container></span> and dependent feature
vector <span class="math notranslate nohighlight"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" tabindex="0" ctxtmenu_counter="1" style="font-size: 113.1%; position: relative;"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msub><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D465 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: -0.15em;"><mjx-mn class="mjx-n" size="s"><mjx-c class="mjx-c31"></mjx-c></mjx-mn></mjx-script></mjx-msub></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>x</mi><mn>1</mn></msub></math></mjx-assistive-mml></mjx-container></span> through <span class="math notranslate nohighlight"><mjx-container class="MathJax CtxtMenu_Attached_0" jax="CHTML" tabindex="0" ctxtmenu_counter="2" style="font-size: 113.1%; position: relative;"><mjx-math class="MJX-TEX" aria-hidden="true"><mjx-msub><mjx-mi class="mjx-i"><mjx-c class="mjx-c1D465 TEX-I"></mjx-c></mjx-mi><mjx-script style="vertical-align: -0.15em;"><mjx-mi class="mjx-i" size="s"><mjx-c class="mjx-c1D45B TEX-I"></mjx-c></mjx-mi></mjx-script></mjx-msub></mjx-math><mjx-assistive-mml unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>x</mi><mi>n</mi></msub></math></mjx-assistive-mml></mjx-container></span></p></li>
    <li>Decision Tree : <p><strong>Decision Trees (DTs)</strong> are a non-parametric supervised learning method used
for <a class="reference internal" href="#tree-classification"><span class="std std-ref">classification</span></a> and <a class="reference internal" href="#tree-regression"><span class="std std-ref">regression</span></a>. The goal is to create a model that predicts the value of a
target variable by learning simple decision rules inferred from the data
features. A tree can be seen as a piecewise constant approximation.</p> </li>
    <li>Random Forest Classifier : <p>A random forest is a meta estimator that fits a number of classifying decision trees on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. </p> </li>
    <li>Multi-Layer Perceptron : <p>MLPClassifier stands for Multi-layer Perceptron classifier which in the name itself connects to a Neural Network. Unlike other classification algorithms such as Support Vectors or Naive Bayes Classifier, MLPClassifier relies on an underlying Neural Network to perform the task of classification.</p> </li>
    
</ul>


## Results 

<ul>
    <li><b>Gaussian Naive Bayes : <i>97.57 %</i> </b></li>
    <li><b>Decision Trees : <i>96.00 %</i> </b> </li>
    <li><b>Random Forest Classifier : <i>98.11 %</i> </b> </li>
    <li><b>Multi-Layer Preceptron : <i>96.68 %</i> </b> </li>
    
</ul>


## Conclusion 

Random Forest Classifier works best on the said data compared to the other models. 

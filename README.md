# api documentation for  [machine_learning (v0.1.1)](http://joonku.com/project/machine_learning)  [![npm package](https://img.shields.io/npm/v/npmdoc-machine_learning.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-machine_learning) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-machine_learning.svg)](https://travis-ci.org/npmdoc/node-npmdoc-machine_learning)
#### Machine learning library for Node.js. You can also use this library in browser.

[![NPM](https://nodei.co/npm/machine_learning.png?downloads=true)](https://www.npmjs.com/package/machine_learning)

[![apidoc](https://npmdoc.github.io/node-npmdoc-machine_learning/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-machine_learning_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-machine_learning/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-machine_learning/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-machine_learning/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joon-Ku Kang",
        "email": "junku901@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/junku901/machine_learning/issues"
    },
    "dependencies": {},
    "description": "Machine learning library for Node.js. You can also use this library in browser.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "74a2ec84eeda7392ec6dd8209bab3f4d1b5cd44f",
        "tarball": "https://registry.npmjs.org/machine_learning/-/machine_learning-0.1.1.tgz"
    },
    "engines": {
        "node": "*"
    },
    "homepage": "http://joonku.com/project/machine_learning",
    "keywords": [
        "machine learning",
        "ml",
        "neural network",
        "svm",
        "support vector machine",
        "kmeans",
        "knn",
        "k nearest neighbors",
        "decision tree",
        "genetic algorithm",
        "nmf",
        "non-negative matrix factorization"
    ],
    "license": "MIT",
    "main": "./lib/machine_learning",
    "maintainers": [
        {
            "name": "junku901",
            "email": "junku901@gmail.com"
        }
    ],
    "name": "machine_learning",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/junku901/machine_learning.git"
    },
    "scripts": {},
    "version": "0.1.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module machine_learning](#apidoc.module.machine_learning)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>DecisionTree (options)](#apidoc.element.machine_learning.DecisionTree)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>HiddenLayer (settings)](#apidoc.element.machine_learning.HiddenLayer)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>KNN (options)](#apidoc.element.machine_learning.KNN)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>LogisticRegression (settings)](#apidoc.element.machine_learning.LogisticRegression)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>MLP (settings)](#apidoc.element.machine_learning.MLP)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>SVM (options)](#apidoc.element.machine_learning.SVM)
1.  object <span class="apidocSignatureSpan">machine_learning.</span>DecisionTree.prototype
1.  object <span class="apidocSignatureSpan">machine_learning.</span>HiddenLayer.prototype
1.  object <span class="apidocSignatureSpan">machine_learning.</span>KNN.prototype
1.  object <span class="apidocSignatureSpan">machine_learning.</span>LogisticRegression.prototype
1.  object <span class="apidocSignatureSpan">machine_learning.</span>MLP.prototype
1.  object <span class="apidocSignatureSpan">machine_learning.</span>SVM.prototype
1.  object <span class="apidocSignatureSpan">machine_learning.</span>kmeans
1.  object <span class="apidocSignatureSpan">machine_learning.</span>math
1.  object <span class="apidocSignatureSpan">machine_learning.</span>nmf
1.  object <span class="apidocSignatureSpan">machine_learning.</span>optimize
1.  object <span class="apidocSignatureSpan">machine_learning.</span>utils

#### [module machine_learning.DecisionTree](#apidoc.module.machine_learning.DecisionTree)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>DecisionTree (options)](#apidoc.element.machine_learning.DecisionTree.DecisionTree)

#### [module machine_learning.DecisionTree.prototype](#apidoc.module.machine_learning.DecisionTree.prototype)
1.  [function <span class="apidocSignatureSpan">machine_learning.DecisionTree.prototype.</span>build (options)](#apidoc.element.machine_learning.DecisionTree.prototype.build)
1.  [function <span class="apidocSignatureSpan">machine_learning.DecisionTree.prototype.</span>classify (observation)](#apidoc.element.machine_learning.DecisionTree.prototype.classify)
1.  [function <span class="apidocSignatureSpan">machine_learning.DecisionTree.prototype.</span>getTree ()](#apidoc.element.machine_learning.DecisionTree.prototype.getTree)
1.  [function <span class="apidocSignatureSpan">machine_learning.DecisionTree.prototype.</span>print ()](#apidoc.element.machine_learning.DecisionTree.prototype.print)
1.  [function <span class="apidocSignatureSpan">machine_learning.DecisionTree.prototype.</span>prune (mingain)](#apidoc.element.machine_learning.DecisionTree.prototype.prune)

#### [module machine_learning.HiddenLayer](#apidoc.module.machine_learning.HiddenLayer)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>HiddenLayer (settings)](#apidoc.element.machine_learning.HiddenLayer.HiddenLayer)

#### [module machine_learning.HiddenLayer.prototype](#apidoc.module.machine_learning.HiddenLayer.prototype)
1.  [function <span class="apidocSignatureSpan">machine_learning.HiddenLayer.prototype.</span>backPropagate (input)](#apidoc.element.machine_learning.HiddenLayer.prototype.backPropagate)
1.  [function <span class="apidocSignatureSpan">machine_learning.HiddenLayer.prototype.</span>linearOutput (input)](#apidoc.element.machine_learning.HiddenLayer.prototype.linearOutput)
1.  [function <span class="apidocSignatureSpan">machine_learning.HiddenLayer.prototype.</span>output (input)](#apidoc.element.machine_learning.HiddenLayer.prototype.output)
1.  [function <span class="apidocSignatureSpan">machine_learning.HiddenLayer.prototype.</span>sampleHgivenV (input)](#apidoc.element.machine_learning.HiddenLayer.prototype.sampleHgivenV)

#### [module machine_learning.KNN](#apidoc.module.machine_learning.KNN)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>KNN (options)](#apidoc.element.machine_learning.KNN.KNN)

#### [module machine_learning.KNN.prototype](#apidoc.module.machine_learning.KNN.prototype)
1.  [function <span class="apidocSignatureSpan">machine_learning.KNN.prototype.</span>predict (options)](#apidoc.element.machine_learning.KNN.prototype.predict)

#### [module machine_learning.LogisticRegression](#apidoc.module.machine_learning.LogisticRegression)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>LogisticRegression (settings)](#apidoc.element.machine_learning.LogisticRegression.LogisticRegression)

#### [module machine_learning.LogisticRegression.prototype](#apidoc.module.machine_learning.LogisticRegression.prototype)
1.  [function <span class="apidocSignatureSpan">machine_learning.LogisticRegression.prototype.</span>getReconstructionCrossEntropy ()](#apidoc.element.machine_learning.LogisticRegression.prototype.getReconstructionCrossEntropy)
1.  [function <span class="apidocSignatureSpan">machine_learning.LogisticRegression.prototype.</span>predict (x)](#apidoc.element.machine_learning.LogisticRegression.prototype.predict)
1.  [function <span class="apidocSignatureSpan">machine_learning.LogisticRegression.prototype.</span>set (property, value)](#apidoc.element.machine_learning.LogisticRegression.prototype.set)
1.  [function <span class="apidocSignatureSpan">machine_learning.LogisticRegression.prototype.</span>train (settings)](#apidoc.element.machine_learning.LogisticRegression.prototype.train)

#### [module machine_learning.MLP](#apidoc.module.machine_learning.MLP)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>MLP (settings)](#apidoc.element.machine_learning.MLP.MLP)

#### [module machine_learning.MLP.prototype](#apidoc.module.machine_learning.MLP.prototype)
1.  [function <span class="apidocSignatureSpan">machine_learning.MLP.prototype.</span>getReconstructionCrossEntropy ()](#apidoc.element.machine_learning.MLP.prototype.getReconstructionCrossEntropy)
1.  [function <span class="apidocSignatureSpan">machine_learning.MLP.prototype.</span>predict (x)](#apidoc.element.machine_learning.MLP.prototype.predict)
1.  [function <span class="apidocSignatureSpan">machine_learning.MLP.prototype.</span>set (property, value)](#apidoc.element.machine_learning.MLP.prototype.set)
1.  [function <span class="apidocSignatureSpan">machine_learning.MLP.prototype.</span>train (settings)](#apidoc.element.machine_learning.MLP.prototype.train)

#### [module machine_learning.SVM](#apidoc.module.machine_learning.SVM)
1.  [function <span class="apidocSignatureSpan">machine_learning.</span>SVM (options)](#apidoc.element.machine_learning.SVM.SVM)

#### [module machine_learning.SVM.prototype](#apidoc.module.machine_learning.SVM.prototype)
1.  [function <span class="apidocSignatureSpan">machine_learning.SVM.prototype.</span>f (x)](#apidoc.element.machine_learning.SVM.prototype.f)
1.  [function <span class="apidocSignatureSpan">machine_learning.SVM.prototype.</span>predict (x)](#apidoc.element.machine_learning.SVM.prototype.predict)
1.  [function <span class="apidocSignatureSpan">machine_learning.SVM.prototype.</span>train (options)](#apidoc.element.machine_learning.SVM.prototype.train)

#### [module machine_learning.kmeans](#apidoc.module.machine_learning.kmeans)
1.  [function <span class="apidocSignatureSpan">machine_learning.kmeans.</span>cluster (options)](#apidoc.element.machine_learning.kmeans.cluster)

#### [module machine_learning.math](#apidoc.module.machine_learning.math)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>activateMat (mat, activation)](#apidoc.element.machine_learning.math.activateMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>activateTwoMat (mat1, mat2, activation)](#apidoc.element.machine_learning.math.activateTwoMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>activateTwoVec (vec1, vec2, activation)](#apidoc.element.machine_learning.math.activateTwoVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>activateVec (vec, activation)](#apidoc.element.machine_learning.math.activateVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>addMat (mat1, mat2)](#apidoc.element.machine_learning.math.addMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>addMatScalar (mat, scalar)](#apidoc.element.machine_learning.math.addMatScalar)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>addMatVec (mat, vec)](#apidoc.element.machine_learning.math.addMatVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>addVec (vec1, vec2)](#apidoc.element.machine_learning.math.addVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>covarianceVecs (vecs)](#apidoc.element.machine_learning.math.covarianceVecs)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>dSigmoid (x)](#apidoc.element.machine_learning.math.dSigmoid)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>dotVec (vec1, vec2)](#apidoc.element.machine_learning.math.dotVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>euclidean (x1, x2)](#apidoc.element.machine_learning.math.euclidean)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>fillMat (row, col, value)](#apidoc.element.machine_learning.math.fillMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>fillVec (n, value)](#apidoc.element.machine_learning.math.fillVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>gaussian (x, sigma)](#apidoc.element.machine_learning.math.gaussian)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>getNormVec (vec)](#apidoc.element.machine_learning.math.getNormVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>identity (n)](#apidoc.element.machine_learning.math.identity)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>maxMat (mat)](#apidoc.element.machine_learning.math.maxMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>maxVec (vec)](#apidoc.element.machine_learning.math.maxVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>meanMat (mat)](#apidoc.element.machine_learning.math.meanMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>meanMatAxis (mat, axis)](#apidoc.element.machine_learning.math.meanMatAxis)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>meanVec (vec)](#apidoc.element.machine_learning.math.meanVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>meanVecs (vecs)](#apidoc.element.machine_learning.math.meanVecs)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>minMat (mat)](#apidoc.element.machine_learning.math.minMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>minVec (vec)](#apidoc.element.machine_learning.math.minVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>minusMat (mat1, mat2)](#apidoc.element.machine_learning.math.minusMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>minusMatVec (mat, vec)](#apidoc.element.machine_learning.math.minusMatVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>minusVec (vec1, vec2)](#apidoc.element.machine_learning.math.minusVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>mulMat (mat1, mat2)](#apidoc.element.machine_learning.math.mulMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>mulMatElementWise (mat1, mat2)](#apidoc.element.machine_learning.math.mulMatElementWise)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>mulMatScalar (mat, scalar)](#apidoc.element.machine_learning.math.mulMatScalar)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>mulVecScalar (vec, scalar)](#apidoc.element.machine_learning.math.mulVecScalar)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>normalizeVec (vec)](#apidoc.element.machine_learning.math.normalizeVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>oneMat (row, col)](#apidoc.element.machine_learning.math.oneMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>oneVec (n)](#apidoc.element.machine_learning.math.oneVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>outerVec (vec1, vec2)](#apidoc.element.machine_learning.math.outerVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>pearson (x, y)](#apidoc.element.machine_learning.math.pearson)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>probToBinaryMat (mat)](#apidoc.element.machine_learning.math.probToBinaryMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>randInt (min, max)](#apidoc.element.machine_learning.math.randInt)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>randMat (row, col, lower, upper)](#apidoc.element.machine_learning.math.randMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>randVec (n, lower, upper)](#apidoc.element.machine_learning.math.randVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>randn ()](#apidoc.element.machine_learning.math.randn)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>randnMat (row, col, mean, sigma)](#apidoc.element.machine_learning.math.randnMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>randnVec (n, mean, sigma)](#apidoc.element.machine_learning.math.randnVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>range (start, end, step)](#apidoc.element.machine_learning.math.range)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>shape (mat)](#apidoc.element.machine_learning.math.shape)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>shuffle (arr)](#apidoc.element.machine_learning.math.shuffle)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>sigmoid (x)](#apidoc.element.machine_learning.math.sigmoid)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>softmaxMat (mat)](#apidoc.element.machine_learning.math.softmaxMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>softmaxVec (vec)](#apidoc.element.machine_learning.math.softmaxVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>squareMat (mat)](#apidoc.element.machine_learning.math.squareMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>squareVec (vec)](#apidoc.element.machine_learning.math.squareVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>sumMat (mat)](#apidoc.element.machine_learning.math.sumMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>sumMatAxis (mat, axis)](#apidoc.element.machine_learning.math.sumMatAxis)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>sumVec (vec)](#apidoc.element.machine_learning.math.sumVec)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>transpose (mat)](#apidoc.element.machine_learning.math.transpose)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>zeroMat (row, col)](#apidoc.element.machine_learning.math.zeroMat)
1.  [function <span class="apidocSignatureSpan">machine_learning.math.</span>zeroVec (n)](#apidoc.element.machine_learning.math.zeroVec)

#### [module machine_learning.nmf](#apidoc.module.machine_learning.nmf)
1.  [function <span class="apidocSignatureSpan">machine_learning.nmf.</span>factorize (options)](#apidoc.element.machine_learning.nmf.factorize)

#### [module machine_learning.optimize](#apidoc.module.machine_learning.optimize)
1.  [function <span class="apidocSignatureSpan">machine_learning.optimize.</span>anneal (options)](#apidoc.element.machine_learning.optimize.anneal)
1.  [function <span class="apidocSignatureSpan">machine_learning.optimize.</span>genetic (options)](#apidoc.element.machine_learning.optimize.genetic)
1.  [function <span class="apidocSignatureSpan">machine_learning.optimize.</span>hillclimb (options)](#apidoc.element.machine_learning.optimize.hillclimb)

#### [module machine_learning.utils](#apidoc.module.machine_learning.utils)
1.  [function <span class="apidocSignatureSpan">machine_learning.utils.</span>isNumber (n)](#apidoc.element.machine_learning.utils.isNumber)
1.  object <span class="apidocSignatureSpan">machine_learning.utils.</span>math



# <a name="apidoc.module.machine_learning"></a>[module machine_learning](#apidoc.module.machine_learning)

#### <a name="apidoc.element.machine_learning.DecisionTree"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>DecisionTree (options)](#apidoc.element.machine_learning.DecisionTree)
- description and source-code
```javascript
DecisionTree = function (options) {
    var self = this;
    self.data = options['data'];
    self.result = options['result'];
}
```
- example usage
```shell
...
           ['kiwitobes','UK','no',19],
           ['digg','New Zealand','yes',12],
           ['slashdot','UK','no',21],
           ['google','UK','yes',18],
           ['kiwitobes','France','yes',19]];
var result = ['None','Premium','Basic','Basic','Premium','None','Basic','Premium','None','None','None','None','Basic','None','Basic
','Basic'];

var dt = new ml.DecisionTree({
    data : data,
    result : result
});

dt.build();

// dt.print();
...
```

#### <a name="apidoc.element.machine_learning.HiddenLayer"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>HiddenLayer (settings)](#apidoc.element.machine_learning.HiddenLayer)
- description and source-code
```javascript
HiddenLayer = function (settings) {
    var self = this;
    self.input = settings['input'];

    if(typeof settings['W'] === 'undefined') {
        var a = 1. / settings['n_in'];
        settings['W'] = math.randMat(settings['n_in'],settings['n_out'],-a,a);
    }
    if(typeof settings['b'] === 'undefined')
        settings['b'] = math.zeroVec(settings['n_out']);
    if(typeof settings['activation'] === 'undefined')
        settings['activation'] = math.sigmoid;

    self.W = settings['W'];
    self.b = settings['b'];
    self.activation = settings['activation'];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.KNN"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>KNN (options)](#apidoc.element.machine_learning.KNN)
- description and source-code
```javascript
KNN = function (options) {
    var self = this;
    self.data = options['data'];
    self.result = options['result'];
}
```
- example usage
```shell
...
        [0,0,1,0,1,0,1,1,1,1,0,1,1,1],
        [0,0,0,0,0,0,1,1,1,1,1,1,1,1],
        [1,0,1,0,0,1,1,1,1,1,0,0,1,0]
       ];

var result = [23,12,23,23,45,70,123,73,146,158,64];

var knn = new ml.KNN({
data : data,
result : result
});

var y = knn.predict({
x : [0,0,0,0,0,0,0,1,1,1,1,1,1,1],
k : 3,
...
```

#### <a name="apidoc.element.machine_learning.LogisticRegression"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>LogisticRegression (settings)](#apidoc.element.machine_learning.LogisticRegression)
- description and source-code
```javascript
LogisticRegression = function (settings) {
    var self = this;
    self.x = settings['input'];
    self.y = settings['label'];
    self.W = math.zeroMat(settings['n_in'],settings['n_out']);
    self.b = math.zeroVec(settings['n_out']);
    self.settings = {
        'log level' : 1 // 0 : nothing, 1 : info, 2: warn
    };
}
```
- example usage
```shell
...
var y = [[1, 0],
         [1, 0],
         [1, 0],
         [0, 1],
         [0, 1],
         [0, 1]];

var classifier = new ml.LogisticRegression({
    'input' : x,
    'label' : y,
    'n_in' : 6,
    'n_out' : 2
});

classifier.set('log level',1);
...
```

#### <a name="apidoc.element.machine_learning.MLP"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>MLP (settings)](#apidoc.element.machine_learning.MLP)
- description and source-code
```javascript
MLP = function (settings) {
    var self = this;
    self.x = settings['input'];
    self.y = settings['label'];
    self.sigmoidLayers = [];
    self.nLayers = settings['hidden_layer_sizes'].length;
    self.settings = {
        'log level' : 1 // 0 : nothing, 1 : info, 2: warn
    };
    var i;
    for(i=0 ; i<self.nLayers+1 ; i++) {
        var inputSize, layerInput;
        if(i == 0)
            inputSize = settings['n_ins'];
        else
            inputSize = settings['hidden_layer_sizes'][i-1];

        if(i == 0)
            layerInput = self.x;
        else
            layerInput = self.sigmoidLayers[self.sigmoidLayers.length-1].sampleHgivenV();

        var sigmoidLayer;
        if(i == self.nLayers) {
            sigmoidLayer = new HiddenLayer({
                'input' : layerInput,
                'n_in' : inputSize,
                'n_out' : settings['n_outs'],
                'activation' : math.sigmoid,
                'W' : (typeof settings['w_array'] === 'undefined')? undefined : settings['w_array'][i],
                'b' : (typeof settings['b_array'] === 'undefined')? undefined : settings['b_array'][i]
            });
        } else {
            sigmoidLayer = new HiddenLayer({
                'input' : layerInput,
                'n_in' : inputSize,
                'n_out' : settings['hidden_layer_sizes'][i],
                'activation' : math.sigmoid,
                'W' : (typeof settings['w_array'] === 'undefined')? undefined : settings['w_array'][i],
                'b' : (typeof settings['b_array'] === 'undefined')? undefined : settings['b_array'][i]
            });
        }
        self.sigmoidLayers.push(sigmoidLayer);
    }
}
```
- example usage
```shell
...
var y = [[1, 0],
         [1, 0],
         [1, 0],
         [0, 1],
         [0, 1],
         [0, 1]];

var mlp = new ml.MLP({
    'input' : x,
    'label' : y,
    'n_ins' : 6,
    'n_outs' : 2,
    'hidden_layer_sizes' : [4,4,5]
});
...
```

#### <a name="apidoc.element.machine_learning.SVM"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>SVM (options)](#apidoc.element.machine_learning.SVM)
- description and source-code
```javascript
SVM = function (options) {
    var self = this;
    self.x = options['x'];
    self.y = options['y'];
}
```
- example usage
```shell
...
     [0.2, 0.01, 0.5, 0.,  0.,  0.9],
     [0.,  0.,  0.5, 0.3, 0.5, -2.3],
     [0.,  0.,  0.5, 0.4, 0.5, 4],
     [0.,  0.,  0.5, 0.5, 0.5, -2]];

var y =  [-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,1,1,1,1,1,1,1,1,1,1];

var svm = new ml.SVM({
x : x,
y : y
});

svm.train({
C : 1.1, // default : 1.0. C in SVM.
tol : 1e-5, // default : 1e-4. Higher tolerance --> Higher precision
...
```



# <a name="apidoc.module.machine_learning.DecisionTree"></a>[module machine_learning.DecisionTree](#apidoc.module.machine_learning.DecisionTree)

#### <a name="apidoc.element.machine_learning.DecisionTree.DecisionTree"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>DecisionTree (options)](#apidoc.element.machine_learning.DecisionTree.DecisionTree)
- description and source-code
```javascript
DecisionTree = function (options) {
    var self = this;
    self.data = options['data'];
    self.result = options['result'];
}
```
- example usage
```shell
...
           ['kiwitobes','UK','no',19],
           ['digg','New Zealand','yes',12],
           ['slashdot','UK','no',21],
           ['google','UK','yes',18],
           ['kiwitobes','France','yes',19]];
var result = ['None','Premium','Basic','Basic','Premium','None','Basic','Premium','None','None','None','None','Basic','None','Basic
','Basic'];

var dt = new ml.DecisionTree({
    data : data,
    result : result
});

dt.build();

// dt.print();
...
```



# <a name="apidoc.module.machine_learning.DecisionTree.prototype"></a>[module machine_learning.DecisionTree.prototype](#apidoc.module.machine_learning.DecisionTree.prototype)

#### <a name="apidoc.element.machine_learning.DecisionTree.prototype.build"></a>[function <span class="apidocSignatureSpan">machine_learning.DecisionTree.prototype.</span>build (options)](#apidoc.element.machine_learning.DecisionTree.prototype.build)
- description and source-code
```javascript
build = function (options) {
    var self = this;
    var rows = [];
    var i;
    for(i=0; i<self.data.length; i++) {
        rows.push(self.data[i]);
        rows[i].push(self.result[i]);
    }
    self.tree = buildTree(rows,entropy);
    return self.tree;
}
```
- example usage
```shell
...
var result = ['None','Premium','Basic','Basic','Premium','None','Basic','Premium','None','None','None','None','Basic','None','Basic
','Basic'];

var dt = new ml.DecisionTree({
    data : data,
    result : result
});

dt.build();

// dt.print();

console.log("Classify : ", dt.classify(['(direct)','USA','yes',5]));

dt.prune(1.0); // 1.0 : mingain.
dt.print();
...
```

#### <a name="apidoc.element.machine_learning.DecisionTree.prototype.classify"></a>[function <span class="apidocSignatureSpan">machine_learning.DecisionTree.prototype.</span>classify (observation)](#apidoc.element.machine_learning.DecisionTree.prototype.classify)
- description and source-code
```javascript
classify = function (observation) {
    var self = this;
    return classify(observation,self.tree);
}
```
- example usage
```shell
...
    result : result
});

dt.build();

// dt.print();

console.log("Classify : ", dt.classify(['(direct)','USA','yes',5]));

dt.prune(1.0); // 1.0 : mingain.
dt.print();
'''

## NMF (Non-negative matrix factorization)
'''javascript
...
```

#### <a name="apidoc.element.machine_learning.DecisionTree.prototype.getTree"></a>[function <span class="apidocSignatureSpan">machine_learning.DecisionTree.prototype.</span>getTree ()](#apidoc.element.machine_learning.DecisionTree.prototype.getTree)
- description and source-code
```javascript
getTree = function () {
    return this.tree;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.DecisionTree.prototype.print"></a>[function <span class="apidocSignatureSpan">machine_learning.DecisionTree.prototype.</span>print ()](#apidoc.element.machine_learning.DecisionTree.prototype.print)
- description and source-code
```javascript
print = function () {

    var self = this;
    printTree(self.tree,'');
}
```
- example usage
```shell
...
var dt = new ml.DecisionTree({
    data : data,
    result : result
});

dt.build();

// dt.print();

console.log("Classify : ", dt.classify(['(direct)','USA','yes',5]));

dt.prune(1.0); // 1.0 : mingain.
dt.print();
'''
...
```

#### <a name="apidoc.element.machine_learning.DecisionTree.prototype.prune"></a>[function <span class="apidocSignatureSpan">machine_learning.DecisionTree.prototype.</span>prune (mingain)](#apidoc.element.machine_learning.DecisionTree.prototype.prune)
- description and source-code
```javascript
prune = function (mingain){
    var self = this;
    prune(self.tree,mingain);
}
```
- example usage
```shell
...

dt.build();

// dt.print();

console.log("Classify : ", dt.classify(['(direct)','USA','yes',5]));

dt.prune(1.0); // 1.0 : mingain.
dt.print();
'''

## NMF (Non-negative matrix factorization)
'''javascript
var ml = require('machine_learning');
var matrix = [[22,28],
...
```



# <a name="apidoc.module.machine_learning.HiddenLayer"></a>[module machine_learning.HiddenLayer](#apidoc.module.machine_learning.HiddenLayer)

#### <a name="apidoc.element.machine_learning.HiddenLayer.HiddenLayer"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>HiddenLayer (settings)](#apidoc.element.machine_learning.HiddenLayer.HiddenLayer)
- description and source-code
```javascript
HiddenLayer = function (settings) {
    var self = this;
    self.input = settings['input'];

    if(typeof settings['W'] === 'undefined') {
        var a = 1. / settings['n_in'];
        settings['W'] = math.randMat(settings['n_in'],settings['n_out'],-a,a);
    }
    if(typeof settings['b'] === 'undefined')
        settings['b'] = math.zeroVec(settings['n_out']);
    if(typeof settings['activation'] === 'undefined')
        settings['activation'] = math.sigmoid;

    self.W = settings['W'];
    self.b = settings['b'];
    self.activation = settings['activation'];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.machine_learning.HiddenLayer.prototype"></a>[module machine_learning.HiddenLayer.prototype](#apidoc.module.machine_learning.HiddenLayer.prototype)

#### <a name="apidoc.element.machine_learning.HiddenLayer.prototype.backPropagate"></a>[function <span class="apidocSignatureSpan">machine_learning.HiddenLayer.prototype.</span>backPropagate (input)](#apidoc.element.machine_learning.HiddenLayer.prototype.backPropagate)
- description and source-code
```javascript
backPropagate = function (input) { // example+num * n_out matrix
    var self = this;
    if(typeof input === 'undefined')
        throw new Error("No BackPropagation Input.")

    var linearOutput = math.mulMat(input, math.transpose(self.W));
    return linearOutput;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.HiddenLayer.prototype.linearOutput"></a>[function <span class="apidocSignatureSpan">machine_learning.HiddenLayer.prototype.</span>linearOutput (input)](#apidoc.element.machine_learning.HiddenLayer.prototype.linearOutput)
- description and source-code
```javascript
linearOutput = function (input) { // returns the value before activation.
    var self = this;
    if(typeof input !== 'undefined')
        self.input = input;

    var linearOutput = math.addMatVec(math.mulMat(self.input,self.W),self.b);
    return linearOutput;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.HiddenLayer.prototype.output"></a>[function <span class="apidocSignatureSpan">machine_learning.HiddenLayer.prototype.</span>output (input)](#apidoc.element.machine_learning.HiddenLayer.prototype.output)
- description and source-code
```javascript
output = function (input) {
    var self = this;
    if(typeof input !== 'undefined')
        self.input = input;

    var linearOutput = math.addMatVec(math.mulMat(self.input,self.W),self.b);
    return math.activateMat(linearOutput,self.activation);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.HiddenLayer.prototype.sampleHgivenV"></a>[function <span class="apidocSignatureSpan">machine_learning.HiddenLayer.prototype.</span>sampleHgivenV (input)](#apidoc.element.machine_learning.HiddenLayer.prototype.sampleHgivenV)
- description and source-code
```javascript
sampleHgivenV = function (input) {
    var self = this;
    if(typeof input !== 'undefined')
        self.input = input;

    var hMean = self.output();
    var hSample = math.probToBinaryMat(hMean);
    return hSample;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.machine_learning.KNN"></a>[module machine_learning.KNN](#apidoc.module.machine_learning.KNN)

#### <a name="apidoc.element.machine_learning.KNN.KNN"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>KNN (options)](#apidoc.element.machine_learning.KNN.KNN)
- description and source-code
```javascript
KNN = function (options) {
    var self = this;
    self.data = options['data'];
    self.result = options['result'];
}
```
- example usage
```shell
...
        [0,0,1,0,1,0,1,1,1,1,0,1,1,1],
        [0,0,0,0,0,0,1,1,1,1,1,1,1,1],
        [1,0,1,0,0,1,1,1,1,1,0,0,1,0]
       ];

var result = [23,12,23,23,45,70,123,73,146,158,64];

var knn = new ml.KNN({
data : data,
result : result
});

var y = knn.predict({
x : [0,0,0,0,0,0,0,1,1,1,1,1,1,1],
k : 3,
...
```



# <a name="apidoc.module.machine_learning.KNN.prototype"></a>[module machine_learning.KNN.prototype](#apidoc.module.machine_learning.KNN.prototype)

#### <a name="apidoc.element.machine_learning.KNN.prototype.predict"></a>[function <span class="apidocSignatureSpan">machine_learning.KNN.prototype.</span>predict (options)](#apidoc.element.machine_learning.KNN.prototype.predict)
- description and source-code
```javascript
predict = function (options) {
    var self = this;
    var x = options['x'];
    var k = options['k'] || 3;
    var weightf = getWeightedFunction(options['weightf']);
    var distance = getDistanceFunction(options['distance']);
    var distanceList = [];
    var i;
    for(i=0; i<self.data.length; i++)
        distanceList.push([distance(x,self.data[i]),i]);
    distanceList.sort(function(a,b) {return a[0]-b[0];});
    var avg = 0.0;
    var totalWeight = 0, weight;
    for(i=0; i<k; i++) {
        var dist = distanceList[i][0];
        var idx = distanceList[i][1];
        weight = weightf(dist);
        avg += weight * self.result[idx];
        totalWeight += weight;
    }

    avg /= totalWeight;
    return avg;
}
```
- example usage
```shell
...
    'epochs' : training_epochs
});

x = [[1, 1, 0, 0, 0, 0],
     [0, 0, 0, 1, 1, 0],
     [1, 1, 1, 1, 1, 0]];

console.log("Result : ",classifier.predict(x));
'''

## MLP (Multi-Layer Perceptron)
'''javascript
var ml = require('machine_learning');
var x = [[0.4, 0.5, 0.5, 0.,  0.,  0.],
[0.5, 0.3,  0.5, 0.,  0.,  0.],
...
```



# <a name="apidoc.module.machine_learning.LogisticRegression"></a>[module machine_learning.LogisticRegression](#apidoc.module.machine_learning.LogisticRegression)

#### <a name="apidoc.element.machine_learning.LogisticRegression.LogisticRegression"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>LogisticRegression (settings)](#apidoc.element.machine_learning.LogisticRegression.LogisticRegression)
- description and source-code
```javascript
LogisticRegression = function (settings) {
    var self = this;
    self.x = settings['input'];
    self.y = settings['label'];
    self.W = math.zeroMat(settings['n_in'],settings['n_out']);
    self.b = math.zeroVec(settings['n_out']);
    self.settings = {
        'log level' : 1 // 0 : nothing, 1 : info, 2: warn
    };
}
```
- example usage
```shell
...
var y = [[1, 0],
         [1, 0],
         [1, 0],
         [0, 1],
         [0, 1],
         [0, 1]];

var classifier = new ml.LogisticRegression({
    'input' : x,
    'label' : y,
    'n_in' : 6,
    'n_out' : 2
});

classifier.set('log level',1);
...
```



# <a name="apidoc.module.machine_learning.LogisticRegression.prototype"></a>[module machine_learning.LogisticRegression.prototype](#apidoc.module.machine_learning.LogisticRegression.prototype)

#### <a name="apidoc.element.machine_learning.LogisticRegression.prototype.getReconstructionCrossEntropy"></a>[function <span class="apidocSignatureSpan">machine_learning.LogisticRegression.prototype.</span>getReconstructionCrossEntropy ()](#apidoc.element.machine_learning.LogisticRegression.prototype.getReconstructionCrossEntropy)
- description and source-code
```javascript
getReconstructionCrossEntropy = function () {
    var self = this;
    var probYgivenX = math.softmaxMat(math.addMatVec(math.mulMat(self.x,self.W),self.b));
    var a = math.mulMatElementWise(self.y, math.activateMat(probYgivenX,Math.log));
    var b = math.mulMatElementWise(math.mulMatScalar(math.addMatScalar(self.y,-1),-1),
        math.activateMat(math.mulMatScalar(math.addMatScalar(probYgivenX,-1),-1),Math.log));
    var crossEntropy = -math.meanVec(math.sumMatAxis(math.addMat(a,b),1));
    return crossEntropy;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.LogisticRegression.prototype.predict"></a>[function <span class="apidocSignatureSpan">machine_learning.LogisticRegression.prototype.</span>predict (x)](#apidoc.element.machine_learning.LogisticRegression.prototype.predict)
- description and source-code
```javascript
predict = function (x) {
    var self = this;
    return math.softmaxMat(math.addMatVec(math.mulMat(x,self.W),self.b));
}
```
- example usage
```shell
...
    'epochs' : training_epochs
});

x = [[1, 1, 0, 0, 0, 0],
     [0, 0, 0, 1, 1, 0],
     [1, 1, 1, 1, 1, 0]];

console.log("Result : ",classifier.predict(x));
'''

## MLP (Multi-Layer Perceptron)
'''javascript
var ml = require('machine_learning');
var x = [[0.4, 0.5, 0.5, 0.,  0.,  0.],
[0.5, 0.3,  0.5, 0.,  0.,  0.],
...
```

#### <a name="apidoc.element.machine_learning.LogisticRegression.prototype.set"></a>[function <span class="apidocSignatureSpan">machine_learning.LogisticRegression.prototype.</span>set (property, value)](#apidoc.element.machine_learning.LogisticRegression.prototype.set)
- description and source-code
```javascript
set = function (property, value) {
    var self = this;
    self.settings[property] = value;
}
```
- example usage
```shell
...
var classifier = new ml.LogisticRegression({
    'input' : x,
    'label' : y,
    'n_in' : 6,
    'n_out' : 2
});

classifier.set('log level',1);

var training_epochs = 800, lr = 0.01;

classifier.train({
    'lr' : lr,
    'epochs' : training_epochs
});
...
```

#### <a name="apidoc.element.machine_learning.LogisticRegression.prototype.train"></a>[function <span class="apidocSignatureSpan">machine_learning.LogisticRegression.prototype.</span>train (settings)](#apidoc.element.machine_learning.LogisticRegression.prototype.train)
- description and source-code
```javascript
train = function (settings) {
    var self = this;
    var lr = 0.1, epochs = 200;
    if(typeof settings['input'] !== 'undefined')
        self.x = settings['input'];
    if(typeof settings['lr'] !== 'undefined')
        lr = settings['lr'];
    if(typeof settings['epochs'] !== 'undefined')
        epochs = settings['epochs'];
    var i;
    var currentProgress = 1;
    for(i=0;i<epochs;i++) {
        var probYgivenX = math.softmaxMat(math.addMatVec(math.mulMat(self.x,self.W),self.b));
        var deltaY = math.minusMat(self.y,probYgivenX);

        var deltaW = math.mulMat(math.transpose(self.x),deltaY);
        var deltaB = math.meanMatAxis(deltaY,0);

        self.W = math.addMat(self.W,math.mulMatScalar(deltaW,lr));
        self.b = math.addVec(self.b,math.mulVecScalar(deltaB,lr));
        if(self.settings['log level'] > 0) {
            var progress = (1.*i/epochs)*100;
            if(progress > currentProgress) {
                console.log("LogisticRegression",progress.toFixed(0),"% Completed.");
                currentProgress++;
            }
        }
    }
    if(self.settings['log level'] > 0)
        console.log("LogisticRegression Final Cross Entropy : ",self.getReconstructionCrossEntropy());
}
```
- example usage
```shell
...
    'n_out' : 2
});

classifier.set('log level',1);

var training_epochs = 800, lr = 0.01;

classifier.train({
    'lr' : lr,
    'epochs' : training_epochs
});

x = [[1, 1, 0, 0, 0, 0],
[0, 0, 0, 1, 1, 0],
[1, 1, 1, 1, 1, 0]];
...
```



# <a name="apidoc.module.machine_learning.MLP"></a>[module machine_learning.MLP](#apidoc.module.machine_learning.MLP)

#### <a name="apidoc.element.machine_learning.MLP.MLP"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>MLP (settings)](#apidoc.element.machine_learning.MLP.MLP)
- description and source-code
```javascript
MLP = function (settings) {
    var self = this;
    self.x = settings['input'];
    self.y = settings['label'];
    self.sigmoidLayers = [];
    self.nLayers = settings['hidden_layer_sizes'].length;
    self.settings = {
        'log level' : 1 // 0 : nothing, 1 : info, 2: warn
    };
    var i;
    for(i=0 ; i<self.nLayers+1 ; i++) {
        var inputSize, layerInput;
        if(i == 0)
            inputSize = settings['n_ins'];
        else
            inputSize = settings['hidden_layer_sizes'][i-1];

        if(i == 0)
            layerInput = self.x;
        else
            layerInput = self.sigmoidLayers[self.sigmoidLayers.length-1].sampleHgivenV();

        var sigmoidLayer;
        if(i == self.nLayers) {
            sigmoidLayer = new HiddenLayer({
                'input' : layerInput,
                'n_in' : inputSize,
                'n_out' : settings['n_outs'],
                'activation' : math.sigmoid,
                'W' : (typeof settings['w_array'] === 'undefined')? undefined : settings['w_array'][i],
                'b' : (typeof settings['b_array'] === 'undefined')? undefined : settings['b_array'][i]
            });
        } else {
            sigmoidLayer = new HiddenLayer({
                'input' : layerInput,
                'n_in' : inputSize,
                'n_out' : settings['hidden_layer_sizes'][i],
                'activation' : math.sigmoid,
                'W' : (typeof settings['w_array'] === 'undefined')? undefined : settings['w_array'][i],
                'b' : (typeof settings['b_array'] === 'undefined')? undefined : settings['b_array'][i]
            });
        }
        self.sigmoidLayers.push(sigmoidLayer);
    }
}
```
- example usage
```shell
...
var y = [[1, 0],
         [1, 0],
         [1, 0],
         [0, 1],
         [0, 1],
         [0, 1]];

var mlp = new ml.MLP({
    'input' : x,
    'label' : y,
    'n_ins' : 6,
    'n_outs' : 2,
    'hidden_layer_sizes' : [4,4,5]
});
...
```



# <a name="apidoc.module.machine_learning.MLP.prototype"></a>[module machine_learning.MLP.prototype](#apidoc.module.machine_learning.MLP.prototype)

#### <a name="apidoc.element.machine_learning.MLP.prototype.getReconstructionCrossEntropy"></a>[function <span class="apidocSignatureSpan">machine_learning.MLP.prototype.</span>getReconstructionCrossEntropy ()](#apidoc.element.machine_learning.MLP.prototype.getReconstructionCrossEntropy)
- description and source-code
```javascript
getReconstructionCrossEntropy = function () {
    var self = this;
    var reconstructedOutput = self.predict(self.x);
    var a = math.activateTwoMat(self.y,reconstructedOutput,function(x,y){
        return x*Math.log(y);
    });

    var b = math.activateTwoMat(self.y,reconstructedOutput,function(x,y){
        return (1-x)*Math.log(1-y);
    });

    var crossEntropy = -math.meanVec(math.sumMatAxis(math.addMat(a,b),1));
    return crossEntropy
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.MLP.prototype.predict"></a>[function <span class="apidocSignatureSpan">machine_learning.MLP.prototype.</span>predict (x)](#apidoc.element.machine_learning.MLP.prototype.predict)
- description and source-code
```javascript
predict = function (x) {
    var self = this;
    var output = x;
    for(i=0; i<self.nLayers+1 ; i++) {
        output = self.sigmoidLayers[i].output(output);
    }
    return output;
}
```
- example usage
```shell
...
    'epochs' : training_epochs
});

x = [[1, 1, 0, 0, 0, 0],
     [0, 0, 0, 1, 1, 0],
     [1, 1, 1, 1, 1, 0]];

console.log("Result : ",classifier.predict(x));
'''

## MLP (Multi-Layer Perceptron)
'''javascript
var ml = require('machine_learning');
var x = [[0.4, 0.5, 0.5, 0.,  0.,  0.],
[0.5, 0.3,  0.5, 0.,  0.,  0.],
...
```

#### <a name="apidoc.element.machine_learning.MLP.prototype.set"></a>[function <span class="apidocSignatureSpan">machine_learning.MLP.prototype.</span>set (property, value)](#apidoc.element.machine_learning.MLP.prototype.set)
- description and source-code
```javascript
set = function (property, value) {
    var self = this;
    self.settings[property] = value;
}
```
- example usage
```shell
...
var classifier = new ml.LogisticRegression({
    'input' : x,
    'label' : y,
    'n_in' : 6,
    'n_out' : 2
});

classifier.set('log level',1);

var training_epochs = 800, lr = 0.01;

classifier.train({
    'lr' : lr,
    'epochs' : training_epochs
});
...
```

#### <a name="apidoc.element.machine_learning.MLP.prototype.train"></a>[function <span class="apidocSignatureSpan">machine_learning.MLP.prototype.</span>train (settings)](#apidoc.element.machine_learning.MLP.prototype.train)
- description and source-code
```javascript
train = function (settings) {
    var self = this;
    var lr = 0.6, epochs = 1000;
    if(typeof settings['lr'] !== 'undefined')
        lr = settings['lr'];
    if(typeof settings['epochs'] !== 'undefined')
        epochs = settings['epochs'];


    var epoch;
    var currentProgress = 1;
    for(epoch=0 ; epoch < epochs ; epoch++) {

        // Feed Forward
        var i;
        var layerInput = [];
        layerInput.push(self.x);
        for(i=0; i<self.nLayers+1 ; i++) {
            layerInput.push(self.sigmoidLayers[i].output(layerInput[i]));
        }
        var output = layerInput[self.nLayers+1];
        // Back Propagation
        var delta = new Array(self.nLayers + 1);
        delta[self.nLayers] = math.mulMatElementWise(math.minusMat(self.y, output),
            math.activateMat(self.sigmoidLayers[self.nLayers].linearOutput(layerInput[self.nLayers]), math.dSigmoid));

        /*
         self.nLayers = 3 (3 hidden layers)
         delta[3] : ouput layer
         delta[2] : 3rd hidden layer, delta[0] : 1st hidden layer
         */
        for(i = self.nLayers - 1; i>=0 ; i--) {
            delta[i] = math.mulMatElementWise(self.sigmoidLayers[i+1].backPropagate(delta[i+1]),
                math.activateMat(self.sigmoidLayers[i].linearOutput(layerInput[i]), math.dSigmoid));
        }
        // Update Weight, Bias
        for(var i=0; i<self.nLayers+1 ; i++) {
            var deltaW = math.activateMat(math.mulMat(math.transpose(layerInput[i]),delta[i]),function(x){return 1. * x / self.x
.length;})
            var deltaB = math.meanMatAxis(delta[i],0);
            self.sigmoidLayers[i].W = math.addMat(self.sigmoidLayers[i].W,deltaW);
            self.sigmoidLayers[i].b = math.addVec(self.sigmoidLayers[i].b,deltaB);
        }

        if(self.settings['log level'] > 0) {
            var progress = (1.*epoch/epochs)*100;
            if(progress > currentProgress) {
                console.log("MLP",progress.toFixed(0),"% Completed.");
                currentProgress+=8;
            }
        }
    }
    if(self.settings['log level'] > 0)
        console.log("MLP Final Cross Entropy : ",self.getReconstructionCrossEntropy());
}
```
- example usage
```shell
...
    'n_out' : 2
});

classifier.set('log level',1);

var training_epochs = 800, lr = 0.01;

classifier.train({
    'lr' : lr,
    'epochs' : training_epochs
});

x = [[1, 1, 0, 0, 0, 0],
[0, 0, 0, 1, 1, 0],
[1, 1, 1, 1, 1, 0]];
...
```



# <a name="apidoc.module.machine_learning.SVM"></a>[module machine_learning.SVM](#apidoc.module.machine_learning.SVM)

#### <a name="apidoc.element.machine_learning.SVM.SVM"></a>[function <span class="apidocSignatureSpan">machine_learning.</span>SVM (options)](#apidoc.element.machine_learning.SVM.SVM)
- description and source-code
```javascript
SVM = function (options) {
    var self = this;
    self.x = options['x'];
    self.y = options['y'];
}
```
- example usage
```shell
...
     [0.2, 0.01, 0.5, 0.,  0.,  0.9],
     [0.,  0.,  0.5, 0.3, 0.5, -2.3],
     [0.,  0.,  0.5, 0.4, 0.5, 4],
     [0.,  0.,  0.5, 0.5, 0.5, -2]];

var y =  [-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,1,1,1,1,1,1,1,1,1,1];

var svm = new ml.SVM({
x : x,
y : y
});

svm.train({
C : 1.1, // default : 1.0. C in SVM.
tol : 1e-5, // default : 1e-4. Higher tolerance --> Higher precision
...
```



# <a name="apidoc.module.machine_learning.SVM.prototype"></a>[module machine_learning.SVM.prototype](#apidoc.module.machine_learning.SVM.prototype)

#### <a name="apidoc.element.machine_learning.SVM.prototype.f"></a>[function <span class="apidocSignatureSpan">machine_learning.SVM.prototype.</span>f (x)](#apidoc.element.machine_learning.SVM.prototype.f)
- description and source-code
```javascript
f = function (x) {
    var self = this;
    var f = 0, j;
    for(j=0; j<self.x.length; j++)
        f += self.alphas[j] * self.y[j] * self.kernel(self.x[j],x);
    f += self.b;
    return f;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.SVM.prototype.predict"></a>[function <span class="apidocSignatureSpan">machine_learning.SVM.prototype.</span>predict (x)](#apidoc.element.machine_learning.SVM.prototype.predict)
- description and source-code
```javascript
predict = function (x) {
    var self = this;
    if(self.f(x) >= 0)
        return 1;
    else
        return -1;
}
```
- example usage
```shell
...
    'epochs' : training_epochs
});

x = [[1, 1, 0, 0, 0, 0],
     [0, 0, 0, 1, 1, 0],
     [1, 1, 1, 1, 1, 0]];

console.log("Result : ",classifier.predict(x));
'''

## MLP (Multi-Layer Perceptron)
'''javascript
var ml = require('machine_learning');
var x = [[0.4, 0.5, 0.5, 0.,  0.,  0.],
[0.5, 0.3,  0.5, 0.,  0.,  0.],
...
```

#### <a name="apidoc.element.machine_learning.SVM.prototype.train"></a>[function <span class="apidocSignatureSpan">machine_learning.SVM.prototype.</span>train (options)](#apidoc.element.machine_learning.SVM.prototype.train)
- description and source-code
```javascript
train = function (options) {
    var self = this;
    var C = options['C'] || 1.0;
    var tol = options['tol'] || 1e-4;
    var maxPasses = options['max_passes'] || 20;
    var alphatol = options['alpha_tol'] || 1e-5;

    self.kernel = getKernel(options['kernel']);
    self.alphas = math.zeroVec(self.x.length);
    self.b = 0;
    var passes = 0, i;
    var count=0;
    while(passes < maxPasses) {
        var numChangedAlphas = 0;

        for(i=0; i<self.x.length; i++) {

            var E_i = self.f(self.x[i]) - self.y[i];

            if((self.y[i] * E_i < -tol && self.alphas[i] < C) || (self.y[i] * E_i > tol && self.alphas[i] >0)) {

                // Randomly selects j (i != j)
                var j = math.randInt(0,self.x.length-1);
                if(i==j) j = (j+1) % self.x.length;

                var E_j = self.f(self.x[j]) - self.y[j];
                var alpha_i_old = self.alphas[i], alpha_j_old = self.alphas[j];

                // Compute L,H
                var L,H;
                if(self.y[i] !== self.y[j]) {
                    L = Math.max(0, self.alphas[j] - self.alphas[i]);
                    H = Math.min(C, C + self.alphas[j] - self.alphas[i]);
                } else {
                    L = Math.max(0, self.alphas[j] + self.alphas[i] - C);
                    H = Math.min(C, self.alphas[j] + self.alphas[i]);
                }

                if(L === H)
                    continue;

                // Compute ETA
                var ETA = 2 * self.kernel(self.x[i],self.x[j]) - self.kernel(self.x[i],self.x[i]) - self.kernel(self.x[j],self.x
[j]);
                if(ETA >= 0)
                    continue;

                // Clip new value to alpha_j
                self.alphas[j] -= 1.*self.y[j] * (E_i - E_j) / ETA;
                if(self.alphas[j] > H)
                    self.alphas[j] = H;
                else if(self.alphas[j] < L)
                    self.alphas[j] = L;

                if(Math.abs(self.alphas[j] - alpha_j_old) < alphatol)
                    continue;

                // Clip new value to alpha_i
                self.alphas[i] += self.y[i] * self.y[j] * (alpha_j_old - self.alphas[j]);

                // update b
                var b1 = self.b - E_i - self.y[i] * (self.alphas[i] - alpha_i_old) * self.kernel(self.x[i],self.x[i])
                                - self.y[j] * (self.alphas[j] - alpha_j_old) * self.kernel(self.x[i],self.x[j]);
                var b2 = self.b - E_j - self.y[i] * (self.alphas[i] - alpha_i_old) * self.kernel(self.x[i],self.x[j])
                                - self.y[j] * (self.alphas[j] - alpha_j_old) * self.kernel(self.x[j],self.x[j]);

                if(0 < self.alphas[i] && self.alphas[i] < C)
                    self.b = b1;
                else if(0 < self.alphas[j] && self.alphas[j] < C)
                    self.b = b2;
                else
                    self.b = (b1+b2)/2.0;

                numChangedAlphas ++ ;
            } // end-if
        } // end-for
        if(numChangedAlphas == 0)
            passes++;
        else
            passes = 0;
    }
}
```
- example usage
```shell
...
    'n_out' : 2
});

classifier.set('log level',1);

var training_epochs = 800, lr = 0.01;

classifier.train({
    'lr' : lr,
    'epochs' : training_epochs
});

x = [[1, 1, 0, 0, 0, 0],
[0, 0, 0, 1, 1, 0],
[1, 1, 1, 1, 1, 0]];
...
```



# <a name="apidoc.module.machine_learning.kmeans"></a>[module machine_learning.kmeans](#apidoc.module.machine_learning.kmeans)

#### <a name="apidoc.element.machine_learning.kmeans.cluster"></a>[function <span class="apidocSignatureSpan">machine_learning.kmeans.</span>cluster (options)](#apidoc.element.machine_learning.kmeans.cluster)
- description and source-code
```javascript
cluster = function (options) {
    var data = options['data'];
    var k = options['k'];
    var distance = getDistanceFunction(options['distance']);
    var epochs = options['epochs'];
    var init_using_data = options['init_using_data'];
    if(typeof init_using_data === "undefined");
        init_using_data = true;
    var means = getRandomMeans(data,k, init_using_data);

    var epoch, i, j, l;
    var clusters = [];
    for(i=0 ; i<k ; i++)
        clusters.push([]);

    for(epoch=0 ; epoch<epochs ; epoch++) {
        clusters = [];
        for(i=0 ; i<k ; i++)
            clusters.push([]);

        // Find which centroid is the closest for each row
        for(i=0 ; i<data.length ; i++) {
            var bestmatch = 0;
            for(j=0 ; j<k ; j++) {
                if(distance(means[j],data[i]) < distance(means[bestmatch],data[i])) bestmatch = j;
            }
            clusters[bestmatch].push(i);
        }

        // Move the centroids to the average of their members
        for(i=0 ; i<k ; i++) {
            var avgs = [];
            for(j=0 ; j<data[0].length ; j++)
                avgs.push(0.0);
            if(clusters[i].length > 0) {
                for(j=0 ; j<clusters[i].length ; j++) {
                    for(l=0 ; l<data[0].length ; l++) {
                        avgs[l] += data[clusters[i][j]][l];
                    }
                }
                for(j=0 ; j<data[0].length ; j++) {
                    avgs[j] /= clusters[i].length;
                }
                means[i] = avgs;
            }
        }
    }
    return {
        clusters : clusters,
        means : means
    };
}
```
- example usage
```shell
...
        [0,0,0,0,0,0,1,1,1,0,1,1,1,0],
        [0,0,0,0,0,1,1,1,0,1,0,1,1,0],
        [0,0,1,0,1,0,1,1,1,1,0,1,1,1],
        [0,0,0,0,0,0,1,1,1,1,1,1,1,1],
        [1,0,1,0,0,1,1,1,1,1,0,0,1,0]
       ];

var result = ml.kmeans.cluster({
data : data,
k : 4,
epochs: 100,

distance : {type : "pearson"}
// default : {type : 'euclidean'}
// {type : 'pearson'}
...
```



# <a name="apidoc.module.machine_learning.math"></a>[module machine_learning.math](#apidoc.module.machine_learning.math)

#### <a name="apidoc.element.machine_learning.math.activateMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>activateMat (mat, activation)](#apidoc.element.machine_learning.math.activateMat)
- description and source-code
```javascript
activateMat = function (mat, activation) {
    var row = m.shape(mat)[0];
    var col = m.shape(mat)[1];
    var i, j,result = [];
    for(i=0;i<row;i++) {
        var rowVec = [];
        for(j=0;j<col;j++)
            rowVec.push(activation(mat[i][j]));
        result.push(rowVec);
    }
    return result;
}
```
- example usage
```shell
...

HiddenLayer.prototype.output = function(input) {
var self = this;
if(typeof input !== 'undefined')
    self.input = input;

var linearOutput = math.addMatVec(math.mulMat(self.input,self.W),self.b);
return math.activateMat(linearOutput,self.activation);
};

HiddenLayer.prototype.linearOutput = function(input) { // returns the value before activation.
var self = this;
if(typeof input !== 'undefined')
    self.input = input;
...
```

#### <a name="apidoc.element.machine_learning.math.activateTwoMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>activateTwoMat (mat1, mat2, activation)](#apidoc.element.machine_learning.math.activateTwoMat)
- description and source-code
```javascript
activateTwoMat = function (mat1, mat2, activation) {
    if (mat1.length === mat2.length && mat1[0].length === mat2[0].length) {
        var result = new Array(mat1.length);

        for (var x = 0; x < mat1.length; x++) {
            result[x] = new Array(mat1[0].length);
        }

        for (var i = 0; i < result.length; i++) {
            for (var j = 0; j < result[i].length; j++) {
                result[i][j] = activation(mat1[i][j],mat2[i][j]);
            }
        }
        return result;
    } else {
        throw new Error("Matrix shape error : not same");
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.activateTwoVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>activateTwoVec (vec1, vec2, activation)](#apidoc.element.machine_learning.math.activateTwoVec)
- description and source-code
```javascript
activateTwoVec = function (vec1, vec2, activation) {
    if (vec1.length === vec2.length) {
        var result = new Array(vec1.length);
        for (var i = 0; i < result.length; i++) {
            result[i] = activation(vec1[i],vec2[i]);
        }
        return result;
    } else {
        throw new Error("Matrix shape error : not same");
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.activateVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>activateVec (vec, activation)](#apidoc.element.machine_learning.math.activateVec)
- description and source-code
```javascript
activateVec = function (vec, activation) {
    var i, result = [];
    for(i=0;i<vec.length;i++)
        result.push(activation(vec[i]));
    return result;
}
```
- example usage
```shell
...
    mat.push(rowVec);
}
return mat;
};

m.softmaxVec = function(vec) {
var max = m.maxVec(vec);
var preSoftmaxVec = m.activateVec(vec,function(x) {return Math.exp(x - max);})
return m.activateVec(preSoftmaxVec,function(x) {return x/ m.sumVec(preSoftmaxVec)})
};

m.softmaxMat = function(mat) {
var result=[], i;
for(i=0 ; i<mat.length ; i++)
    result.push(m.softmaxVec(mat[i]));
...
```

#### <a name="apidoc.element.machine_learning.math.addMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>addMat (mat1, mat2)](#apidoc.element.machine_learning.math.addMat)
- description and source-code
```javascript
addMat = function (mat1, mat2) {
    if ((mat1.length === mat2.length) && (mat1[0].length === mat2[0].length)) {
        var result = new Array(mat1.length);
        for (var i = 0; i < mat1.length; i++) {
            result[i] = new Array(mat1[i].length);
            for (var j = 0; j < mat1[i].length; j++) {
                result[i][j] = mat1[i][j] + mat2[i][j];
            }
        }
        return result;
    } else {
        throw new Error('Matrix mismatch.');
    }
}
```
- example usage
```shell
...

m.covarianceVecs = function(vecs) {
var mat = m.zeroMat(vecs[0].length,vecs[0].length);
var meanVec = m.meanVecs(vecs);
var i;
for(i=0; i<vecs.length; i++) {
    var a = m.minusVec(vecs[i],meanVec);
    mat = m.addMat(mat, m.mulMat(m.transpose([a]),[a]));
}
return m.activateMat(mat,function(x) { return 1.*x/(vecs.length-1);});
};

m.shuffle = function(arr){
var o = [];
for(var i=0;i<arr.length;i++)
...
```

#### <a name="apidoc.element.machine_learning.math.addMatScalar"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>addMatScalar (mat, scalar)](#apidoc.element.machine_learning.math.addMatScalar)
- description and source-code
```javascript
addMatScalar = function (mat, scalar) {
    var row = m.shape(mat)[0];
    var col = m.shape(mat)[1];
    var i , j,result = [];
    for(i=0 ; i<row ; i++) {
        var rowVec = [];
        for(j=0 ; j<col ; j++) {
            rowVec.push(mat[i][j] + scalar);
        }
        result.push(rowVec);
    }
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.addMatVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>addMatVec (mat, vec)](#apidoc.element.machine_learning.math.addMatVec)
- description and source-code
```javascript
addMatVec = function (mat, vec) {
    if(mat[0].length === vec.length) {
        var result = [];
        var i;
        for(i=0;i<mat.length;i++)
            result.push(m.addVec(mat[i],vec));
        return result;
    } else {
        throw new Error("Length Error : not same.")
    }
}
```
- example usage
```shell
...
}

HiddenLayer.prototype.output = function(input) {
var self = this;
if(typeof input !== 'undefined')
    self.input = input;

var linearOutput = math.addMatVec(math.mulMat(self.input,self.W),self.b);
return math.activateMat(linearOutput,self.activation);
};

HiddenLayer.prototype.linearOutput = function(input) { // returns the value before activation.
var self = this;
if(typeof input !== 'undefined')
    self.input = input;
...
```

#### <a name="apidoc.element.machine_learning.math.addVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>addVec (vec1, vec2)](#apidoc.element.machine_learning.math.addVec)
- description and source-code
```javascript
addVec = function (vec1, vec2) {
    if(vec1.length === vec2.length) {
        var result = [];
        var i;
        for(i=0;i<vec1.length;i++)
            result.push(vec1[i]+vec2[i]);
        return result;
    } else {
        throw new Error("Length Error : not same.")
    }
}
```
- example usage
```shell
...
}

m.addMatVec = function(mat,vec) {
    if(mat[0].length === vec.length) {
        var result = [];
        var i;
        for(i=0;i<mat.length;i++)
            result.push(m.addVec(mat[i],vec));
        return result;
    } else {
        throw new Error("Length Error : not same.")
    }
}

m.minusMatVec = function(mat,vec) {
...
```

#### <a name="apidoc.element.machine_learning.math.covarianceVecs"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>covarianceVecs (vecs)](#apidoc.element.machine_learning.math.covarianceVecs)
- description and source-code
```javascript
covarianceVecs = function (vecs) {
    var mat = m.zeroMat(vecs[0].length,vecs[0].length);
    var meanVec = m.meanVecs(vecs);
    var i;
    for(i=0; i<vecs.length; i++) {
        var a = m.minusVec(vecs[i],meanVec);
        mat = m.addMat(mat, m.mulMat(m.transpose([a]),[a]));
    }
    return m.activateMat(mat,function(x) { return 1.*x/(vecs.length-1);});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.dSigmoid"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>dSigmoid (x)](#apidoc.element.machine_learning.math.dSigmoid)
- description and source-code
```javascript
dSigmoid = function (x){
    a = m.sigmoid(x);
    return a * (1. - a);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.dotVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>dotVec (vec1, vec2)](#apidoc.element.machine_learning.math.dotVec)
- description and source-code
```javascript
dotVec = function (vec1, vec2) {
    if (vec1.length === vec2.length) {
        var result = 0;
        for (var i = 0; i < vec1.length; i++) {
            result += vec1[i] * vec2[i];
        }
        return result;
    } else {
        throw new Error("Vector mismatch");
    }
}
```
- example usage
```shell
...
            result[x] = new Array(mat2[0].length);
        }


        var mat2_T = m.transpose(mat2);
        for (var i = 0; i < result.length; i++) {
            for (var j = 0; j < result[i].length; j++) {
                result[i][j] = m.dotVec(mat1[i],mat2_T[j]);
            }
        }
        return result;
    } else {
        throw new Error("Array mismatch");
    }
};
...
```

#### <a name="apidoc.element.machine_learning.math.euclidean"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>euclidean (x1, x2)](#apidoc.element.machine_learning.math.euclidean)
- description and source-code
```javascript
euclidean = function (x1, x2) {
    var i;
    var distance = 0;
    for(i=0 ; i<x1.length; i++) {
        var dx = x1[i] - x2[i];
        distance += dx * dx;
    }
    return Math.sqrt(distance);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.fillMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>fillMat (row, col, value)](#apidoc.element.machine_learning.math.fillMat)
- description and source-code
```javascript
fillMat = function (row, col, value) {
    var mat = [];
    while(mat.length < row) {
        var rowVec = [];
        while(rowVec.length < col)
            rowVec.push(value);
        mat.push(rowVec);
    }
    return mat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.fillVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>fillVec (n, value)](#apidoc.element.machine_learning.math.fillVec)
- description and source-code
```javascript
fillVec = function (n, value) {
    var vec = [];
    while(vec.length < n)
        vec.push(value);
    return vec;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.gaussian"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>gaussian (x, sigma)](#apidoc.element.machine_learning.math.gaussian)
- description and source-code
```javascript
gaussian = function (x, sigma) {
    sigma = sigma || 10.0;
    return Math.exp(-1.*x*x/(2*sigma*sigma));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.getNormVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>getNormVec (vec)](#apidoc.element.machine_learning.math.getNormVec)
- description and source-code
```javascript
getNormVec = function (vec) {
    var i;
    var sqsum = 0;
    for(i=0; i<vec.length; i++)
        sqsum += vec[i] * vec[i];
    return Math.sqrt(sqsum);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.identity"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>identity (n)](#apidoc.element.machine_learning.math.identity)
- description and source-code
```javascript
identity = function (n) {
    var result = new Array(n);

    for (var i = 0; i < n ; i++) {
        result[i] = new Array(n);
        for (var j = 0; j < n; j++) {
            result[i][j] = (i === j) ? 1 : 0;
        }
    }

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.maxMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>maxMat (mat)](#apidoc.element.machine_learning.math.maxMat)
- description and source-code
```javascript
maxMat = function (mat) {
    var max = mat[0][0];
    var i = mat.length;
    while (i--) {
        for(var j=0;j<mat[0].length;j++) {
            if(mat[i][j] < max)
                max = mat[i][j];
        }
    }
    return max;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.maxVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>maxVec (vec)](#apidoc.element.machine_learning.math.maxVec)
- description and source-code
```javascript
maxVec = function (vec) {
    var max = vec[0];
    var i = vec.length;
    while (i--) {
        if (vec[i] > max)
            max = vec[i];
    }
    return max;
}
```
- example usage
```shell
...
        rowVec.push(value);
    mat.push(rowVec);
}
return mat;
};

m.softmaxVec = function(vec) {
var max = m.maxVec(vec);
var preSoftmaxVec = m.activateVec(vec,function(x) {return Math.exp(x - max);})
return m.activateVec(preSoftmaxVec,function(x) {return x/ m.sumVec(preSoftmaxVec)})
};

m.softmaxMat = function(mat) {
var result=[], i;
for(i=0 ; i<mat.length ; i++)
...
```

#### <a name="apidoc.element.machine_learning.math.meanMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>meanMat (mat)](#apidoc.element.machine_learning.math.meanMat)
- description and source-code
```javascript
meanMat = function (mat) {
    var row = mat.length;
    var col = mat[0].length;
    return 1. * m.sumMat(mat) / (row * col);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.meanMatAxis"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>meanMatAxis (mat, axis)](#apidoc.element.machine_learning.math.meanMatAxis)
- description and source-code
```javascript
meanMatAxis = function (mat, axis) {
    // default axis 0;
    // axis 0 : mean of col vector . axis 1 : mean of row vector
    if(axis === 1) {
        var row = m.shape(mat)[0];
        var i ;
        var result = [];
        for(i=0 ; i<row; i++)
            result.push(m.meanVec(mat[i]));
        return result;
    } else {
        mat_T = m.transpose(mat);
        return m.meanMatAxis(mat_T,1);
    }
}
```
- example usage
```shell
...
    var i ;
    var result = [];
    for(i=0 ; i<row; i++)
        result.push(m.meanVec(mat[i]));
    return result;
} else {
    mat_T = m.transpose(mat);
    return m.meanMatAxis(mat_T,1);
}
};

m.squareVec = function(vec) {
var squareVec = [];
var i;
for(i=0;i<vec.length;i++) {
...
```

#### <a name="apidoc.element.machine_learning.math.meanVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>meanVec (vec)](#apidoc.element.machine_learning.math.meanVec)
- description and source-code
```javascript
meanVec = function (vec) {
    return 1. * m.sumVec(vec) / vec.length;
}
```
- example usage
```shell
...
    // default axis 0;
    // axis 0 : mean of col vector . axis 1 : mean of row vector
    if(axis === 1) {
        var row = m.shape(mat)[0];
        var i ;
        var result = [];
        for(i=0 ; i<row; i++)
            result.push(m.meanVec(mat[i]));
        return result;
    } else {
        mat_T = m.transpose(mat);
        return m.meanMatAxis(mat_T,1);
    }
};
...
```

#### <a name="apidoc.element.machine_learning.math.meanVecs"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>meanVecs (vecs)](#apidoc.element.machine_learning.math.meanVecs)
- description and source-code
```javascript
meanVecs = function (vecs) {
    var sum = m.zeroVec(vecs[0].length);
    var i;
    for(i=0; i<vecs.length; i++)
        sum = m.addVec(sum,vecs[i]);
    return m.activateVec(sum,function(x) {return 1.*x/vecs.length;});
}
```
- example usage
```shell
...
    for(i=0; i<vecs.length; i++)
        sum = m.addVec(sum,vecs[i]);
    return m.activateVec(sum,function(x) {return 1.*x/vecs.length;});
};

m.covarianceVecs = function(vecs) {
    var mat = m.zeroMat(vecs[0].length,vecs[0].length);
    var meanVec = m.meanVecs(vecs);
    var i;
    for(i=0; i<vecs.length; i++) {
        var a = m.minusVec(vecs[i],meanVec);
        mat = m.addMat(mat, m.mulMat(m.transpose([a]),[a]));
    }
    return m.activateMat(mat,function(x) { return 1.*x/(vecs.length-1);});
};
...
```

#### <a name="apidoc.element.machine_learning.math.minMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>minMat (mat)](#apidoc.element.machine_learning.math.minMat)
- description and source-code
```javascript
minMat = function (mat) {
    var min = mat[0][0];
    var i = mat.length;
    while (i--) {
        for(var j=0;j<mat[0].length;j++) {
            if(mat[i][j] < min)
                min = mat[i][j];
        }
    }
    return min;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.minVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>minVec (vec)](#apidoc.element.machine_learning.math.minVec)
- description and source-code
```javascript
minVec = function (vec) {
    var min = vec[0];
    var i = vec.length;
    while (i--) {
        if (vec[i] < min)
            min = vec[i];
    }
    return min;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.minusMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>minusMat (mat1, mat2)](#apidoc.element.machine_learning.math.minusMat)
- description and source-code
```javascript
minusMat = function (mat1, mat2) {
    if ((mat1.length === mat2.length) && (mat1[0].length === mat2[0].length)) {
        var result = new Array(mat1.length);
        for (var i = 0; i < mat1.length; i++) {
            result[i] = new Array(mat1[i].length);
            for (var j = 0; j < mat1[i].length; j++) {
                result[i][j] = mat1[i][j] - mat2[i][j];
            }
        }
        return result;
    } else {
        throw new Error('Matrix mismatch.');
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.minusMatVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>minusMatVec (mat, vec)](#apidoc.element.machine_learning.math.minusMatVec)
- description and source-code
```javascript
minusMatVec = function (mat, vec) {
    if(mat[0].length === vec.length) {
        var result = [];
        var i;
        for(i=0;i<mat.length;i++)
            result.push(m.minusVec(mat[i],vec));
        return result;
    } else {
        throw new Error("Length Error : not same.")
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.minusVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>minusVec (vec1, vec2)](#apidoc.element.machine_learning.math.minusVec)
- description and source-code
```javascript
minusVec = function (vec1, vec2) {
    if(vec1.length === vec2.length) {
        var result = [];
        var i;
        for(i=0;i<vec1.length;i++)
            result.push(vec1[i]-vec2[i]);
        return result;
    } else {
        throw new Error("Length Error : not same.")
    }
}
```
- example usage
```shell
...
}

m.minusMatVec = function(mat,vec) {
    if(mat[0].length === vec.length) {
        var result = [];
        var i;
        for(i=0;i<mat.length;i++)
            result.push(m.minusVec(mat[i],vec));
        return result;
    } else {
        throw new Error("Length Error : not same.")
    }
}

m.addMat = function (mat1, mat2) {
...
```

#### <a name="apidoc.element.machine_learning.math.mulMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>mulMat (mat1, mat2)](#apidoc.element.machine_learning.math.mulMat)
- description and source-code
```javascript
mulMat = function (mat1, mat2) {
    if (mat1[0].length === mat2.length) {
        var result = new Array(mat1.length);

        for (var x = 0; x < mat1.length; x++) {
            result[x] = new Array(mat2[0].length);
        }


        var mat2_T = m.transpose(mat2);
        for (var i = 0; i < result.length; i++) {
            for (var j = 0; j < result[i].length; j++) {
                result[i][j] = m.dotVec(mat1[i],mat2_T[j]);
            }
        }
        return result;
    } else {
        throw new Error("Array mismatch");
    }
}
```
- example usage
```shell
...
}

HiddenLayer.prototype.output = function(input) {
var self = this;
if(typeof input !== 'undefined')
    self.input = input;

var linearOutput = math.addMatVec(math.mulMat(self.input,self.W),self.b);
return math.activateMat(linearOutput,self.activation);
};

HiddenLayer.prototype.linearOutput = function(input) { // returns the value before activation.
var self = this;
if(typeof input !== 'undefined')
    self.input = input;
...
```

#### <a name="apidoc.element.machine_learning.math.mulMatElementWise"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>mulMatElementWise (mat1, mat2)](#apidoc.element.machine_learning.math.mulMatElementWise)
- description and source-code
```javascript
mulMatElementWise = function (mat1, mat2) {
    if (mat1.length === mat2.length && mat1[0].length === mat2[0].length) {
        var result = new Array(mat1.length);

        for (var x = 0; x < mat1.length; x++) {
            result[x] = new Array(mat1[0].length);
        }

        for (var i = 0; i < result.length; i++) {
            for (var j = 0; j < result[i].length; j++) {
                result[i][j] = mat1[i][j] * mat2[i][j]
            }
        }
        return result;
    } else {
        throw new Error("Matrix shape error : not same");
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.mulMatScalar"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>mulMatScalar (mat, scalar)](#apidoc.element.machine_learning.math.mulMatScalar)
- description and source-code
```javascript
mulMatScalar = function (mat, scalar) {
    var row = m.shape(mat)[0];
    var col = m.shape(mat)[1];
    var i , j,result = [];
    for(i=0 ; i<row ; i++) {
        var rowVec = [];
        for(j=0 ; j<col ; j++) {
            rowVec.push(mat[i][j] * scalar);
        }
        result.push(rowVec);
    }
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.mulVecScalar"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>mulVecScalar (vec, scalar)](#apidoc.element.machine_learning.math.mulVecScalar)
- description and source-code
```javascript
mulVecScalar = function (vec, scalar) {
    var i, result = [];
    for(i=0;i<vec.length;i++)
        result.push(vec[i]*scalar);
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.normalizeVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>normalizeVec (vec)](#apidoc.element.machine_learning.math.normalizeVec)
- description and source-code
```javascript
normalizeVec = function (vec) {
    var i;
    var newVec = [],tot = 0;
    for(i=0; i<vec.length; i++)
        tot += vec[i];
    for(i=0; i<vec.length;i++)
        newVec.push(1.*vec[i]/tot);
    return newVec;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.oneMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>oneMat (row, col)](#apidoc.element.machine_learning.math.oneMat)
- description and source-code
```javascript
oneMat = function (row, col) {
    var mat = [];
    while(mat.length < row)
        mat.push(m.oneVec(col));
    return mat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.oneVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>oneVec (n)](#apidoc.element.machine_learning.math.oneVec)
- description and source-code
```javascript
oneVec = function (n) {
    var vec = [];
    while(vec.length < n)
        vec.push(1);
    return vec;
}
```
- example usage
```shell
...
    vec.push(1);
return vec;
};

m.oneMat = function(row,col) {
var mat = [];
while(mat.length < row)
    mat.push(m.oneVec(col));
return mat;
};

m.randVec = function(n,lower,upper) {
lower = (typeof lower !== 'undefined') ? lower : 0;
upper = (typeof upper !== 'undefined') ? upper : 1;
var vec = [];
...
```

#### <a name="apidoc.element.machine_learning.math.outerVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>outerVec (vec1, vec2)](#apidoc.element.machine_learning.math.outerVec)
- description and source-code
```javascript
outerVec = function (vec1, vec2) {
    var mat1 = m.transpose([vec1]);
    var mat2 = [vec2];
    return m.mulMat(mat1,mat2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.pearson"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>pearson (x, y)](#apidoc.element.machine_learning.math.pearson)
- description and source-code
```javascript
pearson = function (x, y)
{
    var xy = [];
    var x2 = [];
    var y2 = [];

    for(var i=0; i<x.length; i++)
    {
        xy.push(x[i] * y[i]);
        x2.push(x[i] * x[i]);
        y2.push(y[i] * y[i]);
    }

    var sum_x = 0;
    var sum_y = 0;
    var sum_xy = 0;
    var sum_x2 = 0;
    var sum_y2 = 0;

    for(var i=0; i<x.length; i++)
    {
        sum_x += x[i];
        sum_y += y[i];
        sum_xy += xy[i];
        sum_x2 += x2[i];
        sum_y2 += y2[i];
    }

    var step1 = (x.length * sum_xy) - (sum_x * sum_y);
    var step2 = (x.length * sum_x2) - (sum_x * sum_x);
    var step3 = (x.length * sum_y2) - (sum_y * sum_y);
    var step4 = Math.sqrt(step2 * step3);
    var answer = step1 / step4;

    return answer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.probToBinaryMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>probToBinaryMat (mat)](#apidoc.element.machine_learning.math.probToBinaryMat)
- description and source-code
```javascript
probToBinaryMat = function (mat) {
    var row = m.shape(mat)[0];
    var col = m.shape(mat)[1];
    var i,j;
    var result = [];

    for(i=0;i<row;i++) {
        var rowVec = [];
        for(j=0;j<col;j++) {
            if(Math.random() < mat[i][j])
                rowVec.push(1);
            else
                rowVec.push(0);
        }
        result.push(rowVec);
    }
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.randInt"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>randInt (min, max)](#apidoc.element.machine_learning.math.randInt)
- description and source-code
```javascript
randInt = function (min, max) {
  var rand = Math.random() * (max - min + 0.9999) + min
  return Math.floor(rand);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.randMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>randMat (row, col, lower, upper)](#apidoc.element.machine_learning.math.randMat)
- description and source-code
```javascript
randMat = function (row, col, lower, upper) {
    lower = (typeof lower !== 'undefined') ? lower : 0;
    upper = (typeof upper !== 'undefined') ? upper : 1;
    var mat = [];
    while(mat.length < row)
        mat.push(m.randVec(col,lower,upper));
    return mat;
}
```
- example usage
```shell
...
var math = require('./utils').math;
let HiddenLayer = module.exports = function (settings) {
var self = this;
self.input = settings['input'];

if(typeof settings['W'] === 'undefined') {
    var a = 1. / settings['n_in'];
    settings['W'] = math.randMat(settings['n_in'],settings['n_out'],-a,a);
}
if(typeof settings['b'] === 'undefined')
    settings['b'] = math.zeroVec(settings['n_out']);
if(typeof settings['activation'] === 'undefined')
    settings['activation'] = math.sigmoid;

self.W = settings['W'];
...
```

#### <a name="apidoc.element.machine_learning.math.randVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>randVec (n, lower, upper)](#apidoc.element.machine_learning.math.randVec)
- description and source-code
```javascript
randVec = function (n, lower, upper) {
    lower = (typeof lower !== 'undefined') ? lower : 0;
    upper = (typeof upper !== 'undefined') ? upper : 1;
    var vec = [];
    while(vec.length < n)
        vec.push(lower + (upper-lower) * Math.random());
    return vec;
}
```
- example usage
```shell
...
};

m.randMat = function(row,col,lower,upper) {
lower = (typeof lower !== 'undefined') ? lower : 0;
upper = (typeof upper !== 'undefined') ? upper : 1;
var mat = [];
while(mat.length < row)
    mat.push(m.randVec(col,lower,upper));
return mat;
};

m.randnVec = function(n,mean,sigma) {
var vec = [];
while(vec.length < n)
    vec.push(mean+sigma* m.randn());
...
```

#### <a name="apidoc.element.machine_learning.math.randn"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>randn ()](#apidoc.element.machine_learning.math.randn)
- description and source-code
```javascript
randn = function () {
    // generate random guassian distribution number. (mean : 0, standard deviation : 1)
    var v1, v2, s;

    do {
        v1 = 2 * Math.random() - 1;   // -1.0 ~ 1.0 까지의 값
        v2 = 2 * Math.random() - 1;   // -1.0 ~ 1.0 까지의 값
        s = v1 * v1 + v2 * v2;
    } while (s >= 1 || s == 0);

    s = Math.sqrt( (-2 * Math.log(s)) / s );
    return v1 * s;
}
```
- example usage
```shell
...
    mat.push(m.randVec(col,lower,upper));
return mat;
};

m.randnVec = function(n,mean,sigma) {
var vec = [];
while(vec.length < n)
    vec.push(mean+sigma* m.randn());
return vec;
};

m.randnMat = function(row,col,mean,sigma) {
var mat = [];
while(mat.length < row)
    mat.push(m.randnVec(col,mean,sigma));
...
```

#### <a name="apidoc.element.machine_learning.math.randnMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>randnMat (row, col, mean, sigma)](#apidoc.element.machine_learning.math.randnMat)
- description and source-code
```javascript
randnMat = function (row, col, mean, sigma) {
    var mat = [];
    while(mat.length < row)
        mat.push(m.randnVec(col,mean,sigma));
    return mat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.randnVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>randnVec (n, mean, sigma)](#apidoc.element.machine_learning.math.randnVec)
- description and source-code
```javascript
randnVec = function (n, mean, sigma) {
    var vec = [];
    while(vec.length < n)
        vec.push(mean+sigma* m.randn());
    return vec;
}
```
- example usage
```shell
...
    vec.push(mean+sigma* m.randn());
return vec;
};

m.randnMat = function(row,col,mean,sigma) {
var mat = [];
while(mat.length < row)
    mat.push(m.randnVec(col,mean,sigma));
return mat;
};

m.identity = function (n) {
var result = new Array(n);

for (var i = 0; i < n ; i++) {
...
```

#### <a name="apidoc.element.machine_learning.math.range"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>range (start, end, step)](#apidoc.element.machine_learning.math.range)
- description and source-code
```javascript
range = function (start, end, step) {
    var ret = [];
    if(typeof step === "undefined")
        step = 1;
    if(typeof end === "undefined") {
        end = start;
        start = 0;
    }
    for(var i=start;i<end;i+=step)
        ret.push(i);
    return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.shape"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>shape (mat)](#apidoc.element.machine_learning.math.shape)
- description and source-code
```javascript
shape = function (mat) {
    var row = mat.length;
    var col = mat[0].length;
    return [row,col];
}
```
- example usage
```shell
...
    return result;
} else {
    throw new Error("Length Error : not same.")
}
};

m.addMatScalar = function(mat,scalar) {
var row = m.shape(mat)[0];
var col = m.shape(mat)[1];
var i , j,result = [];
for(i=0 ; i<row ; i++) {
    var rowVec = [];
    for(j=0 ; j<col ; j++) {
        rowVec.push(mat[i][j] + scalar);
    }
...
```

#### <a name="apidoc.element.machine_learning.math.shuffle"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>shuffle (arr)](#apidoc.element.machine_learning.math.shuffle)
- description and source-code
```javascript
shuffle = function (arr){
    var o = [];
    for(var i=0;i<arr.length;i++)
        o.push(arr[i]); // deep copy
    for(var j, x, i = o.length; i; j = parseInt(Math.random() * i), x = o[--i], o[i] = o[j], o[j] = x);
    return o;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.sigmoid"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>sigmoid (x)](#apidoc.element.machine_learning.math.sigmoid)
- description and source-code
```javascript
sigmoid = function (x) {
    var sigmoid = (1. / (1 + Math.exp(-x)))
    if(sigmoid ==1) {
     //   console.warn("Something Wrong!! Sigmoid Function returns 1. Probably javascript float precision problem?\nSlightly Controlled
 value to 1 - 1e-14")
        sigmoid = 0.99999999999999; // Javascript Float Precision Problem.. This is a limit of javascript.
    } else if(sigmoid ==0) {
      //  console.warn("Something Wrong!! Sigmoid Function returns 0. Probably javascript float precision problem?\nSlightly Controlled
 value to 1e-14")
        sigmoid = 1e-14;
    }
    return sigmoid; // sigmoid cannot be 0 or 1;;
}
```
- example usage
```shell
...
  //  console.warn("Something Wrong!! Sigmoid Function returns 0. Probably javascript float precision problem?\nSlightly Controlled
 value to 1e-14")
    sigmoid = 1e-14;
}
return sigmoid; // sigmoid cannot be 0 or 1;;
};

m.dSigmoid = function(x){
a = m.sigmoid(x);
return a * (1. - a);
};

m.probToBinaryMat = function(mat) {
var row = m.shape(mat)[0];
var col = m.shape(mat)[1];
var i,j;
...
```

#### <a name="apidoc.element.machine_learning.math.softmaxMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>softmaxMat (mat)](#apidoc.element.machine_learning.math.softmaxMat)
- description and source-code
```javascript
softmaxMat = function (mat) {
    var result=[], i;
    for(i=0 ; i<mat.length ; i++)
        result.push(m.softmaxVec(mat[i]));
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.softmaxVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>softmaxVec (vec)](#apidoc.element.machine_learning.math.softmaxVec)
- description and source-code
```javascript
softmaxVec = function (vec) {
    var max = m.maxVec(vec);
    var preSoftmaxVec = m.activateVec(vec,function(x) {return Math.exp(x - max);})
    return m.activateVec(preSoftmaxVec,function(x) {return x/ m.sumVec(preSoftmaxVec)})
}
```
- example usage
```shell
...
    var preSoftmaxVec = m.activateVec(vec,function(x) {return Math.exp(x - max);})
    return m.activateVec(preSoftmaxVec,function(x) {return x/ m.sumVec(preSoftmaxVec)})
};

m.softmaxMat = function(mat) {
    var result=[], i;
    for(i=0 ; i<mat.length ; i++)
        result.push(m.softmaxVec(mat[i]));
    return result;
};

m.randInt = function(min,max) {
  var rand = Math.random() * (max - min + 0.9999) + min
  return Math.floor(rand);
}
...
```

#### <a name="apidoc.element.machine_learning.math.squareMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>squareMat (mat)](#apidoc.element.machine_learning.math.squareMat)
- description and source-code
```javascript
squareMat = function (mat) {
    var squareMat = [];
    var i;
    for(i=0;i<mat.length;i++) {
        squareMat.push(m.squareVec(mat[i]));
    }
    return squareMat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.machine_learning.math.squareVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>squareVec (vec)](#apidoc.element.machine_learning.math.squareVec)
- description and source-code
```javascript
squareVec = function (vec) {
    var squareVec = [];
    var i;
    for(i=0;i<vec.length;i++) {
        squareVec.push(vec[i]*vec[i]);
    }
    return squareVec;
}
```
- example usage
```shell
...
return squareVec;
};

m.squareMat = function(mat) {
var squareMat = [];
var i;
for(i=0;i<mat.length;i++) {
    squareMat.push(m.squareVec(mat[i]));
}
return squareMat;
};

m.minVec = function(vec) {
var min = vec[0];
var i = vec.length;
...
```

#### <a name="apidoc.element.machine_learning.math.sumMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>sumMat (mat)](#apidoc.element.machine_learning.math.sumMat)
- description and source-code
```javascript
sumMat = function (mat) {
    var sum = 0;
    var i = mat.length;
    while (i--) {
        for(var j=0;j<mat[0].length;j++)
          sum += mat[i][j];
    }
    return sum;
}
```
- example usage
```shell
...
m.meanVec = function(vec) {
return 1. * m.sumVec(vec) / vec.length;
};

m.meanMat = function(mat) {
var row = mat.length;
var col = mat[0].length;
return 1. * m.sumMat(mat) / (row * col);
};

m.meanMatAxis = function(mat,axis) {
// default axis 0;
// axis 0 : mean of col vector . axis 1 : mean of row vector
if(axis === 1) {
    var row = m.shape(mat)[0];
...
```

#### <a name="apidoc.element.machine_learning.math.sumMatAxis"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>sumMatAxis (mat, axis)](#apidoc.element.machine_learning.math.sumMatAxis)
- description and source-code
```javascript
sumMatAxis = function (mat, axis) {
    // default axis 0;
    // axis 0 : mean of col vector . axis 1 : mean of row vector
    if(axis === 1) {
        var row = m.shape(mat)[0];
        var i ;
        var result = [];
        for(i=0 ; i<row; i++)
            result.push(m.sumVec(mat[i]));
        return result;
    } else {
        mat_T = m.transpose(mat);
        return m.sumMatAxis(mat_T,1);
    }
}
```
- example usage
```shell
...
        var i ;
        var result = [];
        for(i=0 ; i<row; i++)
            result.push(m.sumVec(mat[i]));
        return result;
    } else {
        mat_T = m.transpose(mat);
        return m.sumMatAxis(mat_T,1);
    }
};

m.meanVec = function(vec) {
    return 1. * m.sumVec(vec) / vec.length;
};
...
```

#### <a name="apidoc.element.machine_learning.math.sumVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>sumVec (vec)](#apidoc.element.machine_learning.math.sumVec)
- description and source-code
```javascript
sumVec = function (vec) {
    var sum = 0;
    var i = vec.length;
    while (i--) {
        sum += vec[i];
    }
    return sum;
}
```
- example usage
```shell
...
    // default axis 0;
    // axis 0 : mean of col vector . axis 1 : mean of row vector
    if(axis === 1) {
        var row = m.shape(mat)[0];
        var i ;
        var result = [];
        for(i=0 ; i<row; i++)
            result.push(m.sumVec(mat[i]));
        return result;
    } else {
        mat_T = m.transpose(mat);
        return m.sumMatAxis(mat_T,1);
    }
};
...
```

#### <a name="apidoc.element.machine_learning.math.transpose"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>transpose (mat)](#apidoc.element.machine_learning.math.transpose)
- description and source-code
```javascript
transpose = function (mat) {
    var result = new Array(mat[0].length);
    for (var i = 0; i < mat[0].length; i++) {
        result[i] = new Array(mat.length);
        for (var j = 0; j < mat.length; j++) {
            result[i][j] = mat[j][i];
        }
    }
    return result;
}
```
- example usage
```shell
...
}

HiddenLayer.prototype.backPropagate = function (input) { // example+num * n_out matrix
var self = this;
if(typeof input === 'undefined')
    throw new Error("No BackPropagation Input.")

var linearOutput = math.mulMat(input, math.transpose(self.W));
return linearOutput;
}

HiddenLayer.prototype.sampleHgivenV = function(input) {
var self = this;
if(typeof input !== 'undefined')
    self.input = input;
...
```

#### <a name="apidoc.element.machine_learning.math.zeroMat"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>zeroMat (row, col)](#apidoc.element.machine_learning.math.zeroMat)
- description and source-code
```javascript
zeroMat = function (row, col) {
    var mat = [];
    while(mat.length < row)
        mat.push(m.zeroVec(col));
    return mat;
}
```
- example usage
```shell
...
var i;
for(i=0; i<vecs.length; i++)
    sum = m.addVec(sum,vecs[i]);
return m.activateVec(sum,function(x) {return 1.*x/vecs.length;});
};

m.covarianceVecs = function(vecs) {
var mat = m.zeroMat(vecs[0].length,vecs[0].length);
var meanVec = m.meanVecs(vecs);
var i;
for(i=0; i<vecs.length; i++) {
    var a = m.minusVec(vecs[i],meanVec);
    mat = m.addMat(mat, m.mulMat(m.transpose([a]),[a]));
}
return m.activateMat(mat,function(x) { return 1.*x/(vecs.length-1);});
...
```

#### <a name="apidoc.element.machine_learning.math.zeroVec"></a>[function <span class="apidocSignatureSpan">machine_learning.math.</span>zeroVec (n)](#apidoc.element.machine_learning.math.zeroVec)
- description and source-code
```javascript
zeroVec = function (n) {
    var vec = [];
    while(vec.length < n)
        vec.push(0);
    return vec;
}
```
- example usage
```shell
...
    self.input = settings['input'];

    if(typeof settings['W'] === 'undefined') {
        var a = 1. / settings['n_in'];
        settings['W'] = math.randMat(settings['n_in'],settings['n_out'],-a,a);
    }
    if(typeof settings['b'] === 'undefined')
        settings['b'] = math.zeroVec(settings['n_out']);
    if(typeof settings['activation'] === 'undefined')
        settings['activation'] = math.sigmoid;

    self.W = settings['W'];
    self.b = settings['b'];
    self.activation = settings['activation'];
}
...
```



# <a name="apidoc.module.machine_learning.nmf"></a>[module machine_learning.nmf](#apidoc.module.machine_learning.nmf)

#### <a name="apidoc.element.machine_learning.nmf.factorize"></a>[function <span class="apidocSignatureSpan">machine_learning.nmf.</span>factorize (options)](#apidoc.element.machine_learning.nmf.factorize)
- description and source-code
```javascript
factorize = function (options) {
    var fc = options['features'];
    var matrix = options['matrix'];
    var epochs = options['epochs'];
    var row = math.shape(matrix)[0], col = math.shape(matrix)[1];
    var a = math.randMat(row,fc,0,1);
    var b = math.randMat(fc,col,0,1);

    var i;
    for(i=0 ; i<epochs; i++) {
        var ab = math.mulMat(a,b)
      //  cost = difcost(ab,matrix);
      //  if(i % 10 ==0) console.log("cost ",cost);
      //  if(cost == 0) break;
        var bn = math.mulMat(math.transpose(a),matrix);
        var bd = math.mulMat(math.mulMat(math.transpose(a),a),b);

        b = math.activateTwoMat(math.mulMatElementWise(b,bn),bd,function(x,y){return x/y});

        var an = math.mulMat(matrix, math.transpose(b));
        var ad = math.mulMat(math.mulMat(a,b), math.transpose(b));

        a = math.activateTwoMat(math.mulMatElementWise(a,an),ad,function(x,y){return x/y});
    }
    return [a,b];
}
```
- example usage
```shell
...

## NMF (Non-negative matrix factorization)
'''javascript
var ml = require('machine_learning');
var matrix = [[22,28],
              [49,64]];

var result = ml.nmf.factorize({
    matrix : matrix,
    features : 3,
    epochs : 100
});

console.log("First Matrix : ",result[0]);
console.log("Second Matrix : ",result[1]);
...
```



# <a name="apidoc.module.machine_learning.optimize"></a>[module machine_learning.optimize](#apidoc.module.machine_learning.optimize)

#### <a name="apidoc.element.machine_learning.optimize.anneal"></a>[function <span class="apidocSignatureSpan">machine_learning.optimize.</span>anneal (options)](#apidoc.element.machine_learning.optimize.anneal)
- description and source-code
```javascript
anneal = function (options){
    var domain = options['domain'];
    var costf = options['costf'];
    var temperature = options['temperature'];
    var cool = options['cool'];
    var step = options['step'];
    var callback

    var i;
    var vec = [];
    for(i=0 ; i<domain.length ; i++)
        vec.push(math.randInt(domain[i][0],domain[i][1]));

    while(temperature > 0.1) {
        var idx = math.randInt(0,domain.length - 1);
        var dir = math.randInt(-step,step);
        var newVec = [];
        for(i=0; i<vec.length ; i++)
            newVec.push(vec[i]);
        newVec[idx]+=dir;
        if(newVec[idx] < domain[idx][0]) newVec[idx] = domain[idx][0];
        if(newVec[idx] > domain[idx][1]) newVec[idx] = domain[idx][1];

        var ea = costf(vec);
        var eb = costf(newVec);
        var p = Math.exp(-1.*(eb-ea)/temperature);
        if(eb < ea || Math.random() < p)
            vec = newVec;

        temperature *= cool;
    }

    return vec;
}
```
- example usage
```shell
...
    return cost;
};

var domain = [];
for(var i=0;i<15;i++)
    domain.push([1,70]); // domain[idx][0] : minimum of vec[idx], domain[idx][1] : maximum of vec[idx].

var vec = ml.optimize.anneal({
    domain : domain,
    costf : costf,
    temperature : 100000.0,
    cool : 0.999,
    step : 4
});
...
```

#### <a name="apidoc.element.machine_learning.optimize.genetic"></a>[function <span class="apidocSignatureSpan">machine_learning.optimize.</span>genetic (options)](#apidoc.element.machine_learning.optimize.genetic)
- description and source-code
```javascript
genetic = function (options){
    var domain = options['domain'];
    var costf = options['costf'];
    var population = options['population'];
    var q = options['q'] || 0.3;
    var elite = options['elite'] || population * 0.04;
    var epochs = options['epochs'] || 100;

    var i,j;
    // Initialize population array
    var pop =[];
    for(i=0; i<population; i++) {
        var vec = [];
        for(j=0; j<domain.length; j++)
            vec.push(math.randInt(domain[j][0],domain[j][1]));
        pop.push(vec);
    }
    pop.sort(function(a,b){return costf(a) - costf(b);});

    for(i=0 ; i<epochs ; i++) {
        // elitism
        var newPop = [];
        for(j=0;j<elite;j++)
            newPop.push(pop[j]);

        // compute fitnesses
        var fitnesses = [];
        for(j=0; j<pop.length; j++)
            fitnesses[j] = q * Math.pow(1-q,j);
        fitnesses = math.normalizeVec(fitnesses);

        // crossover, mutate
        for(j=0; j<pop.length - elite;j++) {
            var idx1 = rouletteWheel(fitnesses);
            var idx2 = rouletteWheel(fitnesses);
            var crossovered = crossover(pop[idx1],pop[idx2]);
            var mutated = mutate(crossovered);
            newPop.push(mutated);
        }

        // replacement
        pop = newPop;
        pop.sort(function(a,b){return costf(a) - costf(b);});
       //console.log("Current Cost : ",costf(pop[0]));
    }
    return pop[0];

    function mutate(vec) {
        var idx = math.randInt(0,domain.length - 1);
        var newVec = [];
        var i;
        for(i=0; i<domain.length ; i++)
            newVec.push(vec[i]);
        newVec[idx] += (Math.random() < 0.5) ? 1 : -1;
        if(newVec[idx] < domain[idx][0]) newVec[idx] = domain[idx][0];
        if(newVec[idx] > domain[idx][1]) newVec[idx] = domain[idx][1];
        return newVec;
    }
    function crossover(vec1,vec2) {
        var idx = math.randInt(0,domain.length - 2);
        var newVec = [];
        var i;
        for(i=0; i<idx ; i++)
            newVec.push(vec1[i]);
        for(i=idx; i<domain.length; i++)
            newVec.push(vec2[i]);
        return newVec;
    }
    function rouletteWheel(vec) {
        var a = [0.0];
        var i;
        for(i=0;i<vec.length;i++) {
            a.push(a[i] + vec[i]);
        }
        var rand = Math.random();
        for(i=0;i< a.length;i++) {
            if(rand > a[i] && rand <= a[i+1])
                return i;
        }
        return -1;
    }
}
```
- example usage
```shell
...
return cost;
};

var domain = [];
for(var i=0;i<15;i++)
domain.push([1,70]); // domain[idx][0] : minimum of vec[idx], domain[idx][1] : maximum of vec[idx].

var vec = ml.optimize.genetic({
domain : domain,
costf : costf,
population : 50,
elite : 2, // elitism. number of elite chromosomes.
epochs : 300,
q : 0.3 // Rank-Based Fitness Assignment. fitness = q * (1-q)^(rank-1)
        // higher q --> higher selection pressure
...
```

#### <a name="apidoc.element.machine_learning.optimize.hillclimb"></a>[function <span class="apidocSignatureSpan">machine_learning.optimize.</span>hillclimb (options)](#apidoc.element.machine_learning.optimize.hillclimb)
- description and source-code
```javascript
hillclimb = function (options){
    var domain = options['domain'];
    var costf = options['costf'];

    var i;
    var vec = [];
    for(i=0 ; i<domain.length ; i++)
        vec.push(math.randInt(domain[i][0],domain[i][1]));

    var current, best;

    while(true) {
        var neighbors = [];
        var i,j;

        for(i=0 ; i<domain.length ; i++) {
            if(vec[i] > domain[i][0]) {
                var newVec = [];
                for(j=0 ; j<domain.length ; j++)
                    newVec.push(vec[j]);
                newVec[i]-=1;
                neighbors.push(newVec);
            } else if (vec[i] < domain[i][1]) {
                var newVec = [];
                for(j=0 ; j<domain.length ; j++)
                    newVec.push(vec[j]);
                newVec[i]+=1;
                neighbors.push(newVec);
            }
        }

        current = costf(vec);
        best = current;
        for(i=0 ; i<neighbors.length ; i++) {
            var cost = costf(neighbors[i]);
            if(cost < best) {
                best = cost;
                vec = neighbors[i];
            }
        }
        if(best === current)
            break;
    }
    return vec;
}
```
- example usage
```shell
...
    return cost;
};

var domain = [];
for(var i=0;i<15;i++)
    domain.push([1,70]); // domain[idx][0] : minimum of vec[idx], domain[idx][1] : maximum of vec[idx].

var vec = ml.optimize.hillclimb({
    domain : domain,
    costf : costf
});

console.log("vec : ",vec);
console.log("cost : ",costf(vec));
'''
...
```



# <a name="apidoc.module.machine_learning.utils"></a>[module machine_learning.utils](#apidoc.module.machine_learning.utils)

#### <a name="apidoc.element.machine_learning.utils.isNumber"></a>[function <span class="apidocSignatureSpan">machine_learning.utils.</span>isNumber (n)](#apidoc.element.machine_learning.utils.isNumber)
- description and source-code
```javascript
isNumber = function (n) {
    return !isNaN(parseFloat(n)) && isFinite(n);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

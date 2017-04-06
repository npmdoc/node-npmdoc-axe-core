# api documentation for  [axe-core (v2.1.7)](https://github.com/dequelabs/axe-core#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-axe-core.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-axe-core) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-axe-core.svg)](https://travis-ci.org/npmdoc/node-npmdoc-axe-core)
#### Accessibility engine for automated Web UI testing

[![NPM](https://nodei.co/npm/axe-core.png?downloads=true)](https://www.npmjs.com/package/axe-core)

[![apidoc](https://npmdoc.github.io/node-npmdoc-axe-core/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-axe-core_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-axe-core/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-axe-core/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-axe-core/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/dequelabs/axe-core/issues"
    },
    "contributors": [
        {
            "name": "David Sturley",
            "url": "http://deque.com/"
        },
        {
            "name": "Dylan Barrell",
            "url": "http://deque.com/"
        },
        {
            "name": "Wilco Fiers",
            "url": "http://deque.com/"
        },
        {
            "name": "Dian Fay",
            "url": "http://deque.com/"
        },
        {
            "name": "Marcy Sutton",
            "url": "http://deque.com/"
        }
    ],
    "dependencies": {},
    "description": "Accessibility engine for automated Web UI testing",
    "devDependencies": {
        "babel-plugin-transform-object-rest-spread": "^6.6.5",
        "babel-polyfill": "^6.7.4",
        "babel-preset-es2015": "^6.6.0",
        "babelify": "^7.2.0",
        "blanket": "~1.2.3",
        "chai": "~3.5.0",
        "clone": "~1.0.2",
        "dot": "~1.0.3",
        "grunt": "~0.4.5",
        "grunt-babel": "^6.0.0",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-concat": "~1.0.0",
        "grunt-contrib-connect": "~1.0.1",
        "grunt-contrib-copy": "~1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-uglify": "~1.0.1",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-mocha": "~0.4.13",
        "grunt-parallel": "^0.4.1",
        "grunt-snyk": "^0.1.0",
        "html-entities": "^1.2.0",
        "jquery": "^3.0.0",
        "less": "~2.6.1",
        "mocha": "~2.4.5",
        "phantomjs-prebuilt": "~2.1.7",
        "promise": "~7.1.1",
        "revalidator": "~0.3.1",
        "selenium-webdriver": "~2.53.1"
    },
    "directories": {},
    "dist": {
        "shasum": "4f66f2b3ee3b58ec2d3db4339dd124c5b33b79c3",
        "tarball": "https://registry.npmjs.org/axe-core/-/axe-core-2.1.7.tgz"
    },
    "gitHead": "400135cf9cf1fa45759be9235ea86a2885e80933",
    "homepage": "https://github.com/dequelabs/axe-core#readme",
    "keywords": [
        "Accessibility",
        "a11y",
        "testing",
        "unit",
        "tdd",
        "bdd",
        "aXe"
    ],
    "license": "MPL-2.0",
    "main": "axe.js",
    "maintainers": [
        {
            "name": "circusbred",
            "email": "circusbred@gmail.com"
        },
        {
            "name": "dequelabs",
            "email": "labs@deque.com"
        },
        {
            "name": "dylanb",
            "email": "dylan@barrell.com"
        },
        {
            "name": "marcysutton",
            "email": "marcy.sutton@deque.com"
        }
    ],
    "name": "axe-core",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dequelabs/axe-core.git"
    },
    "scripts": {
        "build": "grunt",
        "test": "grunt test",
        "test-fast": "grunt test-fast"
    },
    "typings": "axe.d.ts",
    "version": "2.1.7"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module axe-core](#apidoc.module.axe-core)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>_load (audit)](#apidoc.element.axe-core._load)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>_runRules (context, options, resolve, reject)](#apidoc.element.axe-core._runRules)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>a11yCheck (context, options, callback)](#apidoc.element.axe-core.a11yCheck)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>addReporter (name, cb, isDefault)](#apidoc.element.axe-core.addReporter)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>cleanup (resolve, reject)](#apidoc.element.axe-core.cleanup)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>configure (spec)](#apidoc.element.axe-core.configure)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>getReporter (reporter)](#apidoc.element.axe-core.getReporter)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>getRules (tags)](#apidoc.element.axe-core.getRules)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>log ()](#apidoc.element.axe-core.log)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>registerPlugin (plugin)](#apidoc.element.axe-core.registerPlugin)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>reset ()](#apidoc.element.axe-core.reset)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>run (context, options, callback)](#apidoc.element.axe-core.run)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>utils.DqElement (element, spec)](#apidoc.element.axe-core.utils.DqElement)
1.  [function <span class="apidocSignatureSpan">axe-core.</span>utils.respondable (win, topic, message, keepalive, callback)](#apidoc.element.axe-core.utils.respondable)
1.  object <span class="apidocSignatureSpan">axe-core.</span>_audit
1.  object <span class="apidocSignatureSpan">axe-core.</span>commons
1.  object <span class="apidocSignatureSpan">axe-core.</span>constants
1.  object <span class="apidocSignatureSpan">axe-core.</span>plugins
1.  object <span class="apidocSignatureSpan">axe-core.</span>utils
1.  object <span class="apidocSignatureSpan">axe-core.</span>utils.DqElement.prototype
1.  string <span class="apidocSignatureSpan">axe-core.</span>source
1.  string <span class="apidocSignatureSpan">axe-core.</span>version

#### [module axe-core.utils](#apidoc.module.axe-core.utils)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>DqElement (element, spec)](#apidoc.element.axe-core.utils.DqElement)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>aggregate (map, values, initial)](#apidoc.element.axe-core.utils.aggregate)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>aggregateChecks (nodeResOriginal)](#apidoc.element.axe-core.utils.aggregateChecks)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>aggregateResult (results)](#apidoc.element.axe-core.utils.aggregateResult)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>aggregateRule (subResults)](#apidoc.element.axe-core.utils.aggregateRule)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>areStylesSet (el, styles, stopAt)](#apidoc.element.axe-core.utils.areStylesSet)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>checkHelper (checkResult, resolve, reject)](#apidoc.element.axe-core.utils.checkHelper)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>clone (obj)](#apidoc.element.axe-core.utils.clone)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>collectResultsFromFrames (context, options, command, parameter, resolve, reject)](#apidoc.element.axe-core.utils.collectResultsFromFrames)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>contains (node, otherNode)](#apidoc.element.axe-core.utils.contains)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>escapeSelector (value)](#apidoc.element.axe-core.utils.escapeSelector)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>extendMetaData (to, from)](#apidoc.element.axe-core.utils.extendMetaData)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>finalizeRuleResult (ruleResult)](#apidoc.element.axe-core.utils.finalizeRuleResult)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>findBy (array, key, value)](#apidoc.element.axe-core.utils.findBy)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>getAllChecks (object)](#apidoc.element.axe-core.utils.getAllChecks)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>getCheckOption (check, ruleID, options)](#apidoc.element.axe-core.utils.getCheckOption)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>getSelector (node)](#apidoc.element.axe-core.utils.getSelector)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>getXpath (node)](#apidoc.element.axe-core.utils.getXpath)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>injectStyle (style)](#apidoc.element.axe-core.utils.injectStyle)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>isHidden (el, recursed)](#apidoc.element.axe-core.utils.isHidden)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>matchesSelector (node, selector)](#apidoc.element.axe-core.utils.matchesSelector)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>mergeResults (frameResults)](#apidoc.element.axe-core.utils.mergeResults)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>nodeSorter (a, b)](#apidoc.element.axe-core.utils.nodeSorter)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>pollyfillElementsFromPoint ()](#apidoc.element.axe-core.utils.pollyfillElementsFromPoint)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>publishMetaData (ruleResult)](#apidoc.element.axe-core.utils.publishMetaData)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>queue ()](#apidoc.element.axe-core.utils.queue)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>respondable (win, topic, message, keepalive, callback)](#apidoc.element.axe-core.utils.respondable)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>ruleShouldRun (rule, context, options)](#apidoc.element.axe-core.utils.ruleShouldRun)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>select (selector, context)](#apidoc.element.axe-core.utils.select)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>sendCommandToFrame (node, parameters, resolve, reject)](#apidoc.element.axe-core.utils.sendCommandToFrame)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>toArray (thing)](#apidoc.element.axe-core.utils.toArray)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>tokenList (str)](#apidoc.element.axe-core.utils.tokenList)

#### [module axe-core.utils.DqElement](#apidoc.module.axe-core.utils.DqElement)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>DqElement (element, spec)](#apidoc.element.axe-core.utils.DqElement.DqElement)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.DqElement.</span>fromFrame (node, frame)](#apidoc.element.axe-core.utils.DqElement.fromFrame)

#### [module axe-core.utils.DqElement.prototype](#apidoc.module.axe-core.utils.DqElement.prototype)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.DqElement.prototype.</span>toJSON ()](#apidoc.element.axe-core.utils.DqElement.prototype.toJSON)

#### [module axe-core.utils.respondable](#apidoc.module.axe-core.utils.respondable)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.</span>respondable (win, topic, message, keepalive, callback)](#apidoc.element.axe-core.utils.respondable.respondable)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.respondable.</span>isInFrame (win)](#apidoc.element.axe-core.utils.respondable.isInFrame)
1.  [function <span class="apidocSignatureSpan">axe-core.utils.respondable.</span>subscribe (topic, callback)](#apidoc.element.axe-core.utils.respondable.subscribe)



# <a name="apidoc.module.axe-core"></a>[module axe-core](#apidoc.module.axe-core)

#### <a name="apidoc.element.axe-core._load"></a>[function <span class="apidocSignatureSpan">axe-core.</span>_load (audit)](#apidoc.element.axe-core._load)
- description and source-code
```javascript
_load = function (audit) {
  'use strict';
  axe.utils.respondable.subscribe('axe.ping', function(data, keepalive, respond) {
    respond({
      axe: true
    });
  });
  axe.utils.respondable.subscribe('axe.start', runCommand);
  axe._audit = new Audit(audit);
}
```
- example usage
```shell
...
  uuid.v1 = v1;
  uuid.v4 = v4;
  uuid.parse = parse;
  uuid.unparse = unparse;
  uuid.BufferClass = BufferClass;
})(window);
'use strict';
axe._load({
  data: {
    rules: {
      accesskeys: {
        description: 'Ensures every accesskey attribute value is unique',
        help: 'accesskey attribute value must be unique'
      },
      'area-alt': {
...
```

#### <a name="apidoc.element.axe-core._runRules"></a>[function <span class="apidocSignatureSpan">axe-core.</span>_runRules (context, options, resolve, reject)](#apidoc.element.axe-core._runRules)
- description and source-code
```javascript
function runRules(context, options, resolve, reject) {
  'use strict';
  context = new Context(context);
  var q = axe.utils.queue();
  var audit = axe._audit;
  if (context.frames.length) {
    q.defer(function(res, rej) {
      axe.utils.collectResultsFromFrames(context, options, 'rules', null, res, rej);
    });
  }
  q.defer(function(res, rej) {
    audit.run(context, options, res, rej);
  });
  q.then(function(data) {
    try {
      // Add wrapper object so that we may use the same "merge" function for results from inside and outside frames
      var results = axe.utils.mergeResults(data.map(function(d) {
        return {
          results: d
        };
      }));
      // after should only run once, so ensure we are in the top level window
      if (context.initiator) {
        results = audit.after(results, options);
        results.forEach(axe.utils.publishMetaData);
        results = results.map(axe.utils.finalizeRuleResult);
      }
      try {
        resolve(results);
      } catch (e) {
        axe.log(e);
      }
    } catch (e) {
      reject(e);
    }
  }).catch(reject);
}
```
- example usage
```shell
...
  }
  var audit = axe._audit;
  if (!audit) {
    throw new Error('No audit configured');
  }
  options.reporter = options.reporter || audit.reporter || 'v2';
  var reporter = axe.getReporter(options.reporter);
  axe._runRules(context, options, function(results) {
    var res = reporter(results, options, callback);
    if (res !== undefined) {
      callback(res);
    }
  }, axe.log);
};
'use strict';
...
```

#### <a name="apidoc.element.axe-core.a11yCheck"></a>[function <span class="apidocSignatureSpan">axe-core.</span>a11yCheck (context, options, callback)](#apidoc.element.axe-core.a11yCheck)
- description and source-code
```javascript
a11yCheck = function (context, options, callback) {
  'use strict';
  if (typeof options === 'function') {
    callback = options;
    options = {};
  }
  if (!options || (typeof options === 'undefined' ? 'undefined' : _typeof(options)) !== 'object') {
    options = {};
  }
  var audit = axe._audit;
  if (!audit) {
    throw new Error('No audit configured');
  }
  options.reporter = options.reporter || audit.reporter || 'v2';
  var reporter = axe.getReporter(options.reporter);
  axe._runRules(context, options, function(results) {
    var res = reporter(results, options, callback);
    if (res !== undefined) {
      callback(res);
    }
  }, axe.log);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.axe-core.addReporter"></a>[function <span class="apidocSignatureSpan">axe-core.</span>addReporter (name, cb, isDefault)](#apidoc.element.axe-core.addReporter)
- description and source-code
```javascript
function registerReporter(name, cb, isDefault) {
  'use strict';
  reporters[name] = cb;
  if (isDefault) {
    defaultReporter = cb;
  }
}
```
- example usage
```shell
...
      return ruleResult;
    });
  });
  return resultObject;
};
'use strict';
/*global helpers */
axe.addReporter('na', function(results, options, callback) {
  'use strict';
  if (typeof options === 'function') {
    callback = options;
    options = {};
  }
  var out = helpers.processAggregate(results, options);
  callback({
...
```

#### <a name="apidoc.element.axe-core.cleanup"></a>[function <span class="apidocSignatureSpan">axe-core.</span>cleanup (resolve, reject)](#apidoc.element.axe-core.cleanup)
- description and source-code
```javascript
function cleanupPlugins(resolve, reject) {
  'use strict';
  if (!axe._audit) {
    throw new Error('No audit configured');
  }
  var q = axe.utils.queue();
  // If a plugin fails it's cleanup, we still want the others to run
  var cleanupErrors = [];
  Object.keys(axe.plugins).forEach(function(key) {
    q.defer(function(res) {
      var rej = function rej(err) {
        cleanupErrors.push(err);
        res();
      };
      try {
        axe.plugins[key].cleanup(res, rej);
      } catch (err) {
        rej(err);
      }
    });
  });
  axe.utils.toArray(document.querySelectorAll('frame, iframe')).forEach(function(frame) {
    q.defer(function(res, rej) {
      return axe.utils.sendCommandToFrame(frame, {
        command: 'cleanup-plugin'
      }, res, rej);
    });
  });
  q.then(function(results) {
    if (cleanupErrors.length === 0) {
      resolve(results);
    } else {
      reject(cleanupErrors);
    }
  }).catch(reject);
}
```
- example usage
```shell
...
Object.keys(axe.plugins).forEach(function(key) {
  q.defer(function(res) {
    var rej = function rej(err) {
      cleanupErrors.push(err);
      res();
    };
    try {
      axe.plugins[key].cleanup(res, rej);
    } catch (err) {
      rej(err);
    }
  });
});
axe.utils.toArray(document.querySelectorAll('frame, iframe')).forEach(function(frame) {
  q.defer(function(res, rej) {
...
```

#### <a name="apidoc.element.axe-core.configure"></a>[function <span class="apidocSignatureSpan">axe-core.</span>configure (spec)](#apidoc.element.axe-core.configure)
- description and source-code
```javascript
function configureChecksRulesAndBranding(spec) {
  'use strict';
  var audit;
  audit = axe._audit;
  if (!audit) {
    throw new Error('No audit configured');
  }
  if (spec.reporter && (typeof spec.reporter === 'function' || reporters[spec.reporter])) {
    audit.reporter = spec.reporter;
  }
  if (spec.checks) {
    spec.checks.forEach(function(check) {
      audit.addCheck(check);
    });
  }
  if (spec.rules) {
    spec.rules.forEach(function(rule) {
      audit.addRule(rule);
    });
  }
  if (typeof spec.branding !== 'undefined') {
    audit.setBranding(spec.branding);
  } else {
    audit._constructHelpUrls();
  }
  if (spec.tagExclude) {
    audit.tagExclude = spec.tagExclude;
  }
}
```
- example usage
```shell
...
 Audit.prototype.addRule = function(spec) {
   'use strict';
   if (spec.metadata) {
     this.data.rules[spec.id] = spec.metadata;
   }
   var rule = this.getRule(spec.id);
   if (rule) {
     rule.configure(spec);
   } else {
     this.rules.push(new Rule(spec, this));
   }
 };
 /**
* Adds a new check to the Audit.  If a Check with specified ID already exists, it will be
* reconfigured
...
```

#### <a name="apidoc.element.axe-core.getReporter"></a>[function <span class="apidocSignatureSpan">axe-core.</span>getReporter (reporter)](#apidoc.element.axe-core.getReporter)
- description and source-code
```javascript
getReporter = function (reporter) {
  'use strict';
  if (typeof reporter === 'string' && reporters[reporter]) {
    return reporters[reporter];
  }
  if (typeof reporter === 'function') {
    return reporter;
  }
  return defaultReporter;
}
```
- example usage
```shell
...
    options = {};
  }
  var audit = axe._audit;
  if (!audit) {
    throw new Error('No audit configured');
  }
  options.reporter = options.reporter || audit.reporter || 'v2';
  var reporter = axe.getReporter(options.reporter);
  axe._runRules(context, options, function(results) {
    var res = reporter(results, options, callback);
    if (res !== undefined) {
      callback(res);
    }
  }, axe.log);
};
...
```

#### <a name="apidoc.element.axe-core.getRules"></a>[function <span class="apidocSignatureSpan">axe-core.</span>getRules (tags)](#apidoc.element.axe-core.getRules)
- description and source-code
```javascript
getRules = function (tags) {
  'use strict';
  tags = tags || [];
  var matchingRules = !tags.length ? axe._audit.rules : axe._audit.rules.filter(function(item) {
    return !!tags.filter(function(tag) {
      return item.tags.indexOf(tag) !== -1;
    }).length;
  });
  var ruleData = axe._audit.data.rules || {};
  return matchingRules.map(function(matchingRule) {
    var rd = ruleData[matchingRule.id] || {};
    return {
      ruleId: matchingRule.id,
      description: rd.description,
      help: rd.help,
      helpUrl: rd.helpUrl,
      tags: matchingRule.tags
    };
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.axe-core.log"></a>[function <span class="apidocSignatureSpan">axe-core.</span>log ()](#apidoc.element.axe-core.log)
- description and source-code
```javascript
log = function () {
  'use strict';
  if ((typeof console === 'undefined' ? 'undefined' : _typeof(console)) === 'object' && console.log) {
    // IE does not support console.log.apply
    Function.prototype.apply.call(console.log, console, arguments);
  }
}
```
- example usage
```shell
...
        results = audit.after(results, options);
        results.forEach(axe.utils.publishMetaData);
        results = results.map(axe.utils.finalizeRuleResult);
      }
      try {
        resolve(results);
      } catch (e) {
        axe.log(e);
      }
    } catch (e) {
      reject(e);
    }
  }).catch(reject);
}
axe._runRules = runRules;
...
```

#### <a name="apidoc.element.axe-core.registerPlugin"></a>[function <span class="apidocSignatureSpan">axe-core.</span>registerPlugin (plugin)](#apidoc.element.axe-core.registerPlugin)
- description and source-code
```javascript
registerPlugin = function (plugin) {
  'use strict';
  axe.plugins[plugin.id] = new Plugin(plugin);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.axe-core.reset"></a>[function <span class="apidocSignatureSpan">axe-core.</span>reset ()](#apidoc.element.axe-core.reset)
- description and source-code
```javascript
function resetConfiguration() {
  'use strict';
  var audit = axe._audit;
  if (!audit) {
    throw new Error('No audit configured');
  }
  audit.resetRulesAndChecks();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.axe-core.run"></a>[function <span class="apidocSignatureSpan">axe-core.</span>run (context, options, callback)](#apidoc.element.axe-core.run)
- description and source-code
```javascript
run = function (context, options, callback) {
  'use strict';
  if (!axe._audit) {
    throw new Error('No audit configured');
  }
  var args = normalizeRunParams(context, options, callback);
  context = args.context;
  options = args.options;
  callback = args.callback;
  // set defaults:
  options.reporter = options.reporter || axe._audit.reporter || 'v1';
  var p = void 0;
  var reject = noop;
  var resolve = noop;
  if (window.Promise && callback === noop) {
    p = new Promise(function(_resolve, _reject) {
      reject = _reject;
      resolve = _resolve;
    });
  }
  axe._runRules(context, options, function(rawResults) {
    var respond = function respond(results) {
      try {
        callback(null, results);
      } catch (e) {
        axe.log(e);
      }
      resolve(results);
    };
    try {
      var reporter = axe.getReporter(options.reporter);
      var results = reporter(rawResults, options, respond);
      if (results !== undefined) {
        respond(results);
      }
    } catch (err) {
      callback(err);
      reject(err);
    }
  }, function(err) {
    callback(err);
    reject(err);
  });
  return p;
}
```
- example usage
```shell
...
'''html
<script src="node_modules/axe-core/axe.min.js" ></script>
'''

Now insert calls at each point in your tests where a new piece of UI becomes visible or exposed:

'''js
axe.run(function (err, results) {
	if (err) throw err;
    ok(results.violations.length === 0, 'Should be no accessibility issues');
    // complete the async call
    ...
});
'''
## Supported Browsers
...
```

#### <a name="apidoc.element.axe-core.utils.DqElement"></a>[function <span class="apidocSignatureSpan">axe-core.</span>utils.DqElement (element, spec)](#apidoc.element.axe-core.utils.DqElement)
- description and source-code
```javascript
function DqElement(element, spec) {
  'use strict';
  spec = spec || {};
<span class="apidocCodeCommentSpan">  /**
* A unique CSS selector for the element
* @type {String}
*/
</span>  this.selector = spec.selector || [ axe.utils.getSelector(element) ];
  /**
* Xpath to the element
*/
  this.xpath = spec.xpath || [ axe.utils.getXpath(element) ];
  /**
* The generated HTML source code of the element
* @type {String}
*/
  this.source = spec.source !== undefined ? spec.source : getSource(element);
  /**
* The element which this object is based off or the containing frame, used for sorting.
* Excluded in toJSON method.
* @type {HTMLElement}
*/
  this.element = element;
}
```
- example usage
```shell
...
          });
          result[r.type] = res;
          if (res.length) {
            hasResults = true;
          }
        });
        if (hasResults) {
          result.node = new axe.utils.DqElement(node);
          ruleResult.nodes.push(result);
        }
      }
      resolveNode();
    }).catch(rejectNode);
  });
}
...
```

#### <a name="apidoc.element.axe-core.utils.respondable"></a>[function <span class="apidocSignatureSpan">axe-core.</span>utils.respondable (win, topic, message, keepalive, callback)](#apidoc.element.axe-core.utils.respondable)
- description and source-code
```javascript
function respondable(win, topic, message, keepalive, callback) {
  var id = uuid.v1();
  post(win, topic, message, id, keepalive, callback);
}
```
- example usage
```shell
...
      resolve(null);
    } else {
      reject(errMsg);
    }
  }, 0);
}, 500);
// send 'axe.ping' to the frame
axe.utils.respondable(win, 'axe.ping', null, undefined, function() {
  clearTimeout(timeout);
  // Give aXe 30s to respond to 'axe.start'
  timeout = setTimeout(function() {
    reject(err('Axe in frame timed out', node));
  }, 3e4);
  // send 'axe.start' and send the callback if it responded
  axe.utils.respondable(win, 'axe.start', parameters, undefined, function(data) {
...
```



# <a name="apidoc.module.axe-core.utils"></a>[module axe-core.utils](#apidoc.module.axe-core.utils)

#### <a name="apidoc.element.axe-core.utils.DqElement"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>DqElement (element, spec)](#apidoc.element.axe-core.utils.DqElement)
- description and source-code
```javascript
function DqElement(element, spec) {
  'use strict';
  spec = spec || {};
<span class="apidocCodeCommentSpan">  /**
* A unique CSS selector for the element
* @type {String}
*/
</span>  this.selector = spec.selector || [ axe.utils.getSelector(element) ];
  /**
* Xpath to the element
*/
  this.xpath = spec.xpath || [ axe.utils.getXpath(element) ];
  /**
* The generated HTML source code of the element
* @type {String}
*/
  this.source = spec.source !== undefined ? spec.source : getSource(element);
  /**
* The element which this object is based off or the containing frame, used for sorting.
* Excluded in toJSON method.
* @type {HTMLElement}
*/
  this.element = element;
}
```
- example usage
```shell
...
          });
          result[r.type] = res;
          if (res.length) {
            hasResults = true;
          }
        });
        if (hasResults) {
          result.node = new axe.utils.DqElement(node);
          ruleResult.nodes.push(result);
        }
      }
      resolveNode();
    }).catch(rejectNode);
  });
}
...
```

#### <a name="apidoc.element.axe-core.utils.aggregate"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>aggregate (map, values, initial)](#apidoc.element.axe-core.utils.aggregate)
- description and source-code
```javascript
aggregate = function (map, values, initial) {
  values = values.slice();
  if (initial) {
    values.push(initial);
  }
  var sorting = values.map(function(val) {
    return map.indexOf(val);
  }).sort();
  // Stupid NodeJS array.sort functor doesn't work!!
  return map[sorting.pop()];
}
```
- example usage
```shell
...
  });
  nodeResult[type].forEach(function(check) {
    return impacts.push(check.impact);
  });
});
// for failed nodes, define the impact
if (nodeResult.priority === axe.constants.FAIL_PRIO) {
  nodeResult.impact = axe.utils.aggregate(axe.constants.impact, impacts);
} else {
  nodeResult.impact = null;
}
// Delete the old result and priority properties
anyAllNone(nodeResult, function(c) {
  delete c.result;
  delete c.priority;
...
```

#### <a name="apidoc.element.axe-core.utils.aggregateChecks"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>aggregateChecks (nodeResOriginal)](#apidoc.element.axe-core.utils.aggregateChecks)
- description and source-code
```javascript
aggregateChecks = function (nodeResOriginal) {
  // Create a copy
  var nodeResult = Object.assign({}, nodeResOriginal);
  // map each result value to a priority
  anyAllNone(nodeResult, function(check, type) {
    var i = checkMap.indexOf(check.result);
    // default to cantTell
    check.priority = i !== -1 ? i : axe.constants.CANTTELL_PRIO;
    if (type === 'none') {
      // For none, reverse the outcome
      check.priority = 4 - check.priority;
    }
  });
  // Find the result with the highest priority
  var priorities = anyAllNone(nodeResult, function(c) {
    return c.priority;
  });
  nodeResult.priority = Math.max(priorities.all.reduce(function(a, b) {
    return Math.max(a, b);
  }, 0), priorities.none.reduce(function(a, b) {
    return Math.max(a, b);
  }, 0), // get the lowest passing of 'any' defaulting
  // to 0 by wrapping around 4 to 0 (inapplicable)
  priorities.any.reduce(function(a, b) {
    return Math.min(a, b);
  }, 4) % 4);
  // Of each type, filter out all results not matching the final priority
  var impacts = [];
  checkTypes.forEach(function(type) {
    nodeResult[type] = nodeResult[type].filter(function(check) {
      return check.priority === nodeResult.priority;
    });
    nodeResult[type].forEach(function(check) {
      return impacts.push(check.impact);
    });
  });
  // for failed nodes, define the impact
  if (nodeResult.priority === axe.constants.FAIL_PRIO) {
    nodeResult.impact = axe.utils.aggregate(axe.constants.impact, impacts);
  } else {
    nodeResult.impact = null;
  }
  // Delete the old result and priority properties
  anyAllNone(nodeResult, function(c) {
    delete c.result;
    delete c.priority;
  });
  // Convert the index to a result string value
  nodeResult.result = axe.constants.results[nodeResult.priority];
  delete nodeResult.priority;
  return nodeResult;
}
```
- example usage
```shell
...
  */
axe.utils.aggregateRule = function(subResults) {
  var ruleResult = {};
  // For each node, retrieve the result and impact
  subResults = subResults.map(function(subResult) {
    // Known result
    if (subResult.any && subResult.all && subResult.none) {
      return axe.utils.aggregateChecks(subResult);
    } else {
      if (Array.isArray(subResult.node)) {
        return axe.utils.finalizeRuleResult(subResult);
      } else {
        throw new TypeError('Invalid Result type');
      }
    }
...
```

#### <a name="apidoc.element.axe-core.utils.aggregateResult"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>aggregateResult (results)](#apidoc.element.axe-core.utils.aggregateResult)
- description and source-code
```javascript
aggregateResult = function (results) {
  var resultObject = {};
  // Create an array for each type
  axe.constants.resultGroups.forEach(function(groupName) {
    return resultObject[groupName] = [];
  });
  // Fill the array with nodes
  results.forEach(function(subResult) {
    if (subResult.error) {
      copyToGroup(resultObject, subResult, axe.constants.CANTTELL_GROUP);
    } else {
      if (subResult.result === axe.constants.NA) {
        copyToGroup(resultObject, subResult, axe.constants.NA_GROUP);
      } else {
        axe.constants.resultGroups.forEach(function(group) {
          if (Array.isArray(subResult[group]) && subResult[group].length > 0) {
            copyToGroup(resultObject, subResult, group);
          }
        });
      }
    }
  });
  return resultObject;
}
```
- example usage
```shell
...
        return res;
      });
    });
  });
}
var resultKeys = axe.constants.resultGroups;
helpers.processAggregate = function(results, options) {
  var resultObject = axe.utils.aggregateResult(results);
  resultObject.timestamp = new Date().toISOString();
  resultObject.url = window.location.href;
  resultKeys.forEach(function(key) {
    resultObject[key] = (resultObject[key] || []).map(function(ruleResult) {
      ruleResult = Object.assign({}, ruleResult);
      if (Array.isArray(ruleResult.nodes) && ruleResult.nodes.length > 0) {
        ruleResult.nodes = ruleResult.nodes.map(function(subResult) {
...
```

#### <a name="apidoc.element.axe-core.utils.aggregateRule"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>aggregateRule (subResults)](#apidoc.element.axe-core.utils.aggregateRule)
- description and source-code
```javascript
aggregateRule = function (subResults) {
  var ruleResult = {};
  // For each node, retrieve the result and impact
  subResults = subResults.map(function(subResult) {
    // Known result
    if (subResult.any && subResult.all && subResult.none) {
      return axe.utils.aggregateChecks(subResult);
    } else {
      if (Array.isArray(subResult.node)) {
        return axe.utils.finalizeRuleResult(subResult);
      } else {
        throw new TypeError('Invalid Result type');
      }
    }
  });
  // Aggregate the result
  var resultList = subResults.map(function(node) {
    return node.result;
  });
  ruleResult.result = axe.utils.aggregate(axe.constants.results, resultList, ruleResult.result);
  // Create an array for each type
  axe.constants.resultGroups.forEach(function(group) {
    return ruleResult[group] = [];
  });
  // Fill the array with nodes
  subResults.forEach(function(subResult) {
    var groupName = axe.constants.resultGroupMap[subResult.result];
    ruleResult[groupName].push(subResult);
  });
  // Take the highest impact of failed rules
  var failGroup = axe.constants.FAIL_GROUP;
  if (ruleResult[failGroup].length > 0) {
    // Get the impact of all violations
    var impactList = ruleResult[failGroup].map(function(failure) {
      return failure.impact;
    });
    ruleResult.impact = axe.utils.aggregate(axe.constants.impact, impactList) || null;
  } else {
    ruleResult.impact = null;
  }
  return ruleResult;
}
```
- example usage
```shell
...
 'use strict';
 /**
* Process rule results, grouping them by outcome
* @param ruleResult {object}
* @return {object}
*/
 axe.utils.finalizeRuleResult = function(ruleResult) {
   Object.assign(ruleResult, axe.utils.aggregateRule(ruleResult.nodes));
   delete ruleResult.nodes;
   return ruleResult;
 };
 'use strict';
 var _typeof = typeof Symbol === 'function' && typeof Symbol.iterator === 'symbol' ? function(obj) {
   return typeof obj;
 } : function(obj) {
...
```

#### <a name="apidoc.element.axe-core.utils.areStylesSet"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>areStylesSet (el, styles, stopAt)](#apidoc.element.axe-core.utils.areStylesSet)
- description and source-code
```javascript
function areStylesSet(el, styles, stopAt) {
  'use strict';
  var styl = window.getComputedStyle(el, null);
  var set = false;
  if (!styl) {
    return false;
  }
  styles.forEach(function(att) {
    if (styl.getPropertyValue(att.property) === att.value) {
      set = true;
    }
  });
  if (set) {
    return true;
  }
  if (el.nodeName.toUpperCase() === stopAt.toUpperCase() || !el.parentNode) {
    return false;
  }
  return areStylesSet(el.parentNode, styles, stopAt);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.axe-core.utils.checkHelper"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>checkHelper (checkResult, resolve, reject)](#apidoc.element.axe-core.utils.checkHelper)
- description and source-code
```javascript
function checkHelper(checkResult, resolve, reject) {
  'use strict';
  return {
    isAsync: false,
    async: function async() {
      this.isAsync = true;
      return function(result) {
        if (result instanceof Error === false) {
          checkResult.value = result;
          resolve(checkResult);
        } else {
          reject(result);
        }
      };
    },
    data: function data(_data) {
      checkResult.data = _data;
    },
    relatedNodes: function relatedNodes(nodes) {
      nodes = nodes instanceof Node ? [ nodes ] : axe.utils.toArray(nodes);
      checkResult.relatedNodes = nodes.map(function(element) {
        return new axe.utils.DqElement(element);
      });
    }
  };
}
```
- example usage
```shell
...
 */
Check.prototype.run = function(node, options, resolve, reject) {
  'use strict';
  options = options || {};
  var enabled = options.hasOwnProperty('enabled') ? options.enabled : this.enabled, checkOptions = options.options || this.options
;
  if (enabled) {
    var checkResult = new CheckResult(this);
    var checkHelper = axe.utils.checkHelper(checkResult, resolve, reject);
    var result;
    try {
      result = this.evaluate.call(checkHelper, node, checkOptions);
    } catch (e) {
      reject(e);
      return;
    }
...
```

#### <a name="apidoc.element.axe-core.utils.clone"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>clone (obj)](#apidoc.element.axe-core.utils.clone)
- description and source-code
```javascript
clone = function (obj) {
  'use strict';
  var index, length, out = obj;
  if (obj !== null && (typeof obj === 'undefined' ? 'undefined' : _typeof(obj)) === 'object') {
    if (Array.isArray(obj)) {
      out = [];
      for (index = 0, length = obj.length; index < length; index++) {
        out[index] = axe.utils.clone(obj[index]);
      }
    } else {
      out = {};
      // jshint forin: false
      for (index in obj) {
        out[index] = axe.utils.clone(obj[index]);
      }
    }
  }
  return out;
}
```
- example usage
```shell
...
  return obj && typeof Symbol === 'function' && obj.constructor === Symbol && obj !== Symbol.prototype ? 'symbol' : typeof obj;
};
/*global Rule, Check, RuleResult, commons: true */
function getDefaultConfiguration(audit) {
  'use strict';
  var config;
  if (audit) {
    config = axe.utils.clone(audit);
    // Commons are configured into axe like everything else,
    // however because things go funky if we have multiple commons objects
    // we're not using the copy of that.
    config.commons = audit.commons;
  } else {
    config = {};
  }
...
```

#### <a name="apidoc.element.axe-core.utils.collectResultsFromFrames"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>collectResultsFromFrames (context, options, command, parameter, resolve, reject)](#apidoc.element.axe-core.utils.collectResultsFromFrames)
- description and source-code
```javascript
function collectResultsFromFrames(context, options, command, parameter, resolve, reject) {
  'use strict';
  var q = axe.utils.queue();
  var frames = context.frames;
  // Tell each axe running in each frame to collect results
  frames.forEach(function(frame) {
    var params = {
      options: options,
      command: command,
      parameter: parameter,
      context: {
        initiator: false,
        page: context.page,
        include: frame.include || [],
        exclude: frame.exclude || []
      }
    };
    q.defer(function(res, rej) {
      var node = frame.node;
      axe.utils.sendCommandToFrame(node, params, function(data) {
        if (data) {
          return res({
            results: data,
            frameElement: node,
            frame: axe.utils.getSelector(node)
          });
        }
        res(null);
      }, rej);
    });
  });
  // Combine results from all frames and give it back
  q.then(function(data) {
    resolve(axe.utils.mergeResults(data));
  }).catch(reject);
}
```
- example usage
```shell
...
  function runRules(context, options, resolve, reject) {
'use strict';
context = new Context(context);
var q = axe.utils.queue();
var audit = axe._audit;
if (context.frames.length) {
  q.defer(function(res, rej) {
    axe.utils.collectResultsFromFrames(context, options, 'rules', null, res, rej);
  });
}
q.defer(function(res, rej) {
  audit.run(context, options, res, rej);
});
q.then(function(data) {
  try {
...
```

#### <a name="apidoc.element.axe-core.utils.contains"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>contains (node, otherNode)](#apidoc.element.axe-core.utils.contains)
- description and source-code
```javascript
contains = function (node, otherNode) {
  //jshint bitwise: false
  'use strict';
  if (typeof node.contains === 'function') {
    return node.contains(otherNode);
  }
  return !!(node.compareDocumentPosition(otherNode) & 16);
}
```
- example usage
```shell
...
* @param  {HTMLElement} otherNode The node to test is contained by 'node'
* @return {Boolean}           Whether 'node' contains 'otherNode'
*/
 axe.utils.contains = function(node, otherNode) {
   //jshint bitwise: false
   'use strict';
   if (typeof node.contains === 'function') {
     return node.contains(otherNode);
   }
   return !!(node.compareDocumentPosition(otherNode) & 16);
 };
 'use strict';
 /*exported DqElement */
 function truncate(str, maxLength) {
   'use strict';
...
```

#### <a name="apidoc.element.axe-core.utils.escapeSelector"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>escapeSelector (value)](#apidoc.element.axe-core.utils.escapeSelector)
- description and source-code
```javascript
escapeSelector = function (value) {
  'use strict';
<span class="apidocCodeCommentSpan">  /*jshint bitwise: true, eqeqeq: false, maxcomplexity: 14, maxstatements: 23, onevar: false, -W041: false */
</span>  var string = String(value);
  var length = string.length;
  var index = -1;
  var codeUnit;
  var result = '';
  var firstCodeUnit = string.charCodeAt(0);
  while (++index < length) {
    codeUnit = string.charCodeAt(index);
    // Note: there’s no need to special-case astral symbols, surrogate
    // pairs, or lone surrogates.
    // If the character is NULL (U+0000), then throw an
    // 'InvalidCharacterError' exception and terminate these steps.
    if (codeUnit == 0) {
      throw new Error('INVALID_CHARACTER_ERR');
    }
    if (// If the character is in the range [\1-\1F] (U+0001 to U+001F) or
    // [\7F-\9F] (U+007F to U+009F), […]
    codeUnit >= 1 && codeUnit <= 31 || codeUnit >= 127 && codeUnit <= 159 || // If the character is the first character and is in
 the range [0-9]
    // (U+0030 to U+0039), […]
    index == 0 && codeUnit >= 48 && codeUnit <= 57 || // If the character is the second character and is in the range [0-9]
    // (U+0030 to U+0039) and the first character is a '-' (U+002D), […]
    index == 1 && codeUnit >= 48 && codeUnit <= 57 && firstCodeUnit == 45) {
      // http://dev.w3.org/csswg/cssom/#escape-a-character-as-code-point
      result += '\\' + codeUnit.toString(16) + ' ';
      continue;
    }
    // If the character is the second character and is '-' (U+002D) and the
    // first character is '-' as well, […]
    if (index == 1 && codeUnit == 45 && firstCodeUnit == 45) {
      // http://dev.w3.org/csswg/cssom/#escape-a-character
      result += '\\' + string.charAt(index);
      continue;
    }
    // If the character is not handled by one of the above rules and is
    // greater than or equal to U+0080, is '-' (U+002D) or '_' (U+005F), or
    // is in one of the ranges [0-9] (U+0030 to U+0039), [A-Z] (U+0041 to
    // U+005A), or [a-z] (U+0061 to U+007A), […]
    if (codeUnit >= 128 || codeUnit == 45 || codeUnit == 95 || codeUnit >= 48 && codeUnit <= 57 || codeUnit >= 65 && codeUnit <=
90 || codeUnit >= 97 && codeUnit <= 122) {
      // the character itself
      result += string.charAt(index);
      continue;
    }
    // Otherwise, the escaped character.
    // http://dev.w3.org/csswg/cssom/#escape-a-character
    result += '\\' + string.charAt(index);
  }
  return result;
}
```
- example usage
```shell
...
* @param  {HTMLElement} node The element to get the selector for
* @return {String}      Unique CSS selector for the node
*/
 axe.utils.getSelector = function getSelector(node) {
   //jshint maxstatements: 21
   'use strict';
   function escape(p) {
     return axe.utils.escapeSelector(p);
   }
   var parts = [], part;
   while (node.parentNode) {
     part = '';
     if (node.id && document.querySelectorAll('#' + axe.utils.escapeSelector(node.id)).length === 1) {
       parts.unshift('#' + axe.utils.escapeSelector(node.id));
       break;
...
```

#### <a name="apidoc.element.axe-core.utils.extendMetaData"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>extendMetaData (to, from)](#apidoc.element.axe-core.utils.extendMetaData)
- description and source-code
```javascript
extendMetaData = function (to, from) {
  Object.assign(to, from);
  Object.keys(from).filter(function(prop) {
    return typeof from[prop] === 'function';
  }).forEach(function(prop) {
    to[prop] = null;
    try {
      to[prop] = from[prop](to);
    } catch (e) {}
  });
}
```
- example usage
```shell
...
   'use strict';
   return function(check) {
     var sourceData = checksData[check.id] || {};
     var messages = sourceData.messages || {};
     var data = Object.assign({}, sourceData);
     delete data.messages;
     data.message = check.result === shouldBeTrue ? messages.pass : messages.fail;
     axe.utils.extendMetaData(check, data);
   };
 }
 /**
* Publish metadata from axe._audit.data
* @param  {RuleResult} result Result to publish to
* @private
*/
...
```

#### <a name="apidoc.element.axe-core.utils.finalizeRuleResult"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>finalizeRuleResult (ruleResult)](#apidoc.element.axe-core.utils.finalizeRuleResult)
- description and source-code
```javascript
finalizeRuleResult = function (ruleResult) {
  Object.assign(ruleResult, axe.utils.aggregateRule(ruleResult.nodes));
  delete ruleResult.nodes;
  return ruleResult;
}
```
- example usage
```shell
...
// For each node, retrieve the result and impact
subResults = subResults.map(function(subResult) {
  // Known result
  if (subResult.any && subResult.all && subResult.none) {
    return axe.utils.aggregateChecks(subResult);
  } else {
    if (Array.isArray(subResult.node)) {
      return axe.utils.finalizeRuleResult(subResult);
    } else {
      throw new TypeError('Invalid Result type');
    }
  }
});
// Aggregate the result
var resultList = subResults.map(function(node) {
...
```

#### <a name="apidoc.element.axe-core.utils.findBy"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>findBy (array, key, value)](#apidoc.element.axe-core.utils.findBy)
- description and source-code
```javascript
findBy = function (array, key, value) {
  if (Array.isArray(array)) {
    return array.find(function(obj) {
      return (typeof obj === 'undefined' ? 'undefined' : _typeof(obj)) === 'object' && obj[key] === value;
    });
  }
}
```
- example usage
```shell
...
* @param  {Array} results  Array of RuleResults to postprocess
* @param  {Mixed} options  Options object to pass into rules and/or disable rules or checks
*/
 Audit.prototype.after = function(results, options) {
   'use strict';
   var rules = this.rules;
   return results.map(function(ruleResult) {
     var rule = axe.utils.findBy(rules, 'id', ruleResult.id);
     return rule.after(ruleResult, options);
   });
 };
 /**
* Get the rule with a given ID
* @param  {string}
* @return {Rule}
...
```

#### <a name="apidoc.element.axe-core.utils.getAllChecks"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>getAllChecks (object)](#apidoc.element.axe-core.utils.getAllChecks)
- description and source-code
```javascript
function getAllChecks(object) {
  'use strict';
  var result = [];
  return result.concat(object.any || []).concat(object.all || []).concat(object.none || []);
}
```
- example usage
```shell
...
* Iterates the rule's Checks looking for ones that have an after function
* @private
* @param  {Rule} rule The rule to check for after checks
* @return {Array}      Checks that have an after function
*/
 function findAfterChecks(rule) {
   'use strict';
   return axe.utils.getAllChecks(rule).map(function(c) {
     var check = rule._audit.checks[c.id || c];
     return check && typeof check.after === 'function' ? check : null;
   }).filter(Boolean);
 }
 /**
* Finds and collates all results for a given Check on a specific Rule
* @private
...
```

#### <a name="apidoc.element.axe-core.utils.getCheckOption"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>getCheckOption (check, ruleID, options)](#apidoc.element.axe-core.utils.getCheckOption)
- description and source-code
```javascript
getCheckOption = function (check, ruleID, options) {
  'use strict';
  var ruleCheckOption = ((options.rules && options.rules[ruleID] || {}).checks || {})[check.id];
  var checkOption = (options.checks || {})[check.id];
  var enabled = check.enabled;
  var opts = check.options;
  if (checkOption) {
    if (checkOption.hasOwnProperty('enabled')) {
      enabled = checkOption.enabled;
    }
    if (checkOption.hasOwnProperty('options')) {
      opts = checkOption.options;
    }
  }
  if (ruleCheckOption) {
    if (ruleCheckOption.hasOwnProperty('enabled')) {
      enabled = ruleCheckOption.enabled;
    }
    if (ruleCheckOption.hasOwnProperty('options')) {
      opts = ruleCheckOption.options;
    }
  }
  return {
    enabled: enabled,
    options: opts
  };
}
```
- example usage
```shell
...
};
Rule.prototype.runChecks = function(type, node, options, resolve, reject) {
  'use strict';
  var self = this;
  var checkQueue = axe.utils.queue();
  this[type].forEach(function(c) {
    var check = self._audit.checks[c.id || c];
    var option = axe.utils.getCheckOption(check, self.id, options);
    checkQueue.defer(function(res, rej) {
      check.run(node, option, res, rej);
    });
  });
  checkQueue.then(function(results) {
    results = results.filter(function(check) {
      return check;
...
```

#### <a name="apidoc.element.axe-core.utils.getSelector"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>getSelector (node)](#apidoc.element.axe-core.utils.getSelector)
- description and source-code
```javascript
function getSelector(node) {
  //jshint maxstatements: 21
  'use strict';
  function escape(p) {
    return axe.utils.escapeSelector(p);
  }
  var parts = [], part;
  while (node.parentNode) {
    part = '';
    if (node.id && document.querySelectorAll('#' + axe.utils.escapeSelector(node.id)).length === 1) {
      parts.unshift('#' + axe.utils.escapeSelector(node.id));
      break;
    }
    if (node.className && typeof node.className === 'string') {
      part = '.' + node.className.trim().split(/\s+/).map(escape).join('.');
      if (part === '.' || siblingsHaveSameSelector(node, part)) {
        part = '';
      }
    }
    if (!part) {
      part = axe.utils.escapeSelector(node.nodeName).toLowerCase();
      if (part === 'html' || part === 'body') {
        parts.unshift(part);
        break;
      }
      if (siblingsHaveSameSelector(node, part)) {
        part += ':nth-of-type(' + nthOfType(node) + ')';
      }
    }
    parts.unshift(part);
    node = node.parentNode;
  }
  return parts.join(' > ');
}
```
- example usage
```shell
...
     }
   }
   return out;
 };
 'use strict';
 function err(message, node) {
   'use strict';
   return new Error(message + ': ' + axe.utils.getSelector(node));
 }
 /**
* Sends a command to an instance of axe in the specified frame
* @param  {Element}  node       The frame element to send the message to
* @param  {Object}   parameters Parameters to pass to the frame
* @param  {Function} callback   Function to call when results from the frame has returned
*/
...
```

#### <a name="apidoc.element.axe-core.utils.getXpath"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>getXpath (node)](#apidoc.element.axe-core.utils.getXpath)
- description and source-code
```javascript
function getXpath(node) {
  var xpathArray = getXPathArray(node);
  return xpathToString(xpathArray);
}
```
- example usage
```shell
...
* A unique CSS selector for the element
* @type {String}
*/
  this.selector = spec.selector || [ axe.utils.getSelector(element) ];
  /**
* Xpath to the element
*/
  this.xpath = spec.xpath || [ axe.utils.getXpath(element) ];
  /**
* The generated HTML source code of the element
* @type {String}
*/
  this.source = spec.source !== undefined ? spec.source : getSource(element);
  /**
* The element which this object is based off or the containing frame, used for sorting.
...
```

#### <a name="apidoc.element.axe-core.utils.injectStyle"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>injectStyle (style)](#apidoc.element.axe-core.utils.injectStyle)
- description and source-code
```javascript
function injectStyle(style) {
  'use strict';
  if (styleSheet && styleSheet.parentNode) {
    // append the style to the existing sheet
    if (styleSheet.styleSheet === undefined) {
      // Not old IE
      styleSheet.appendChild(document.createTextNode(style));
    } else {
      styleSheet.styleSheet.cssText += style;
    }
    return styleSheet;
  }
  if (!style) {
    return;
  }
  var head = document.head || document.getElementsByTagName('head')[0];
  styleSheet = document.createElement('style');
  styleSheet.type = 'text/css';
  if (styleSheet.styleSheet === undefined) {
    // Not old IE
    styleSheet.appendChild(document.createTextNode(style));
  } else {
    styleSheet.styleSheet.cssText = style;
  }
  head.appendChild(styleSheet);
  return styleSheet;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.axe-core.utils.isHidden"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>isHidden (el, recursed)](#apidoc.element.axe-core.utils.isHidden)
- description and source-code
```javascript
function isHidden(el, recursed) {
  'use strict';
  // 9 === Node.DOCUMENT
  if (el.nodeType === 9) {
    return false;
  }
  var style = window.getComputedStyle(el, null);
  if (!style || !el.parentNode || style.getPropertyValue('display') === 'none' || !recursed && // visibility is only accurate on
 the first element
  style.getPropertyValue('visibility') === 'hidden' || el.getAttribute('aria-hidden') === 'true') {
    return true;
  }
  return axe.utils.isHidden(el.parentNode, true);
}
```
- example usage
```shell
...
* Pushes a unique frame onto 'frames' array, filtering any hidden iframes
* @private
* @param  {Array} collection The array of unique frames that is being operated on
* @param  {HTMLElement} frame   The frame to push onto Context
*/
 function pushUniqueFrame(collection, frame) {
   'use strict';
   if (axe.utils.isHidden(frame)) {
     return;
   }
   var fr = axe.utils.findBy(collection, 'node', frame);
   if (!fr) {
     collection.push({
       node: frame,
       include: [],
...
```

#### <a name="apidoc.element.axe-core.utils.matchesSelector"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>matchesSelector (node, selector)](#apidoc.element.axe-core.utils.matchesSelector)
- description and source-code
```javascript
matchesSelector = function (node, selector) {
  if (!method || !node[method]) {
    method = getMethod(node.ownerDocument.defaultView);
  }
  return node[method](selector);
}
```
- example usage
```shell
...
   var index, sibling, siblings = node.parentNode.children;
   if (!siblings) {
     return false;
   }
   var length = siblings.length;
   for (index = 0; index < length; index++) {
     sibling = siblings[index];
     if (sibling !== node && axe.utils.matchesSelector(sibling, selector)) {
       return true;
     }
   }
   return false;
 }
 /**
* Gets a unique CSS selector
...
```

#### <a name="apidoc.element.axe-core.utils.mergeResults"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>mergeResults (frameResults)](#apidoc.element.axe-core.utils.mergeResults)
- description and source-code
```javascript
function mergeResults(frameResults) {
  'use strict';
  var result = [];
  frameResults.forEach(function(frameResult) {
    var results = normalizeResult(frameResult);
    if (!results || !results.length) {
      return;
    }
    results.forEach(function(ruleResult) {
      if (ruleResult.nodes && frameResult.frame) {
        pushFrame(ruleResult.nodes, frameResult.frameElement, frameResult.frame);
      }
      var res = axe.utils.findBy(result, 'id', ruleResult.id);
      if (!res) {
        result.push(ruleResult);
      } else {
        if (ruleResult.nodes.length) {
          spliceNodes(res.nodes, ruleResult.nodes);
        }
      }
    });
  });
  return result;
}
```
- example usage
```shell
...
}
q.defer(function(res, rej) {
  audit.run(context, options, res, rej);
});
q.then(function(data) {
  try {
    // Add wrapper object so that we may use the same "merge" function for results from inside and outside frames
    var results = axe.utils.mergeResults(data.map(function(d) {
      return {
        results: d
      };
    }));
    // after should only run once, so ensure we are in the top level window
    if (context.initiator) {
      results = audit.after(results, options);
...
```

#### <a name="apidoc.element.axe-core.utils.nodeSorter"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>nodeSorter (a, b)](#apidoc.element.axe-core.utils.nodeSorter)
- description and source-code
```javascript
function nodeSorter(a, b) {
<span class="apidocCodeCommentSpan">  /*jshint bitwise: false */
</span>  'use strict';
  if (a === b) {
    return 0;
  }
  if (a.compareDocumentPosition(b) & 4) {
    // a before b
    return -1;
  }
  return 1;
}
```
- example usage
```shell
...
* @return {Array}      The merged and sorted result
*/
function spliceNodes(target, to) {
  'use strict';
  var firstFromFrame = to[0].node, sorterResult, t;
  for (var i = 0, l = target.length; i < l; i++) {
    t = target[i].node;
    sorterResult = axe.utils.nodeSorter(t.element, firstFromFrame.element);
    if (sorterResult > 0 || sorterResult === 0 && firstFromFrame.selector.length < t.selector.length) {
      target.splice.apply(target, [ i, 0 ].concat(to));
      return;
    }
  }
  target.push.apply(target, to);
}
...
```

#### <a name="apidoc.element.axe-core.utils.pollyfillElementsFromPoint"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>pollyfillElementsFromPoint ()](#apidoc.element.axe-core.utils.pollyfillElementsFromPoint)
- description and source-code
```javascript
pollyfillElementsFromPoint = function () {
  if (document.elementsFromPoint) {
    return document.elementsFromPoint;
  }
  if (document.msElementsFromPoint) {
    return document.msElementsFromPoint;
  }
  var usePointer = function() {
    var element = document.createElement('x');
    element.style.cssText = 'pointer-events:auto';
    return element.style.pointerEvents === 'auto';
  }();
  var cssProp = usePointer ? 'pointer-events' : 'visibility';
  var cssDisableVal = usePointer ? 'none' : 'hidden';
  var style = document.createElement('style');
  style.innerHTML = usePointer ? '* { pointer-events: all }' : '* { visibility: visible }';
  return function(x, y) {
    var current, i, d;
    var elements = [];
    var previousPointerEvents = [];
    // startup
    document.head.appendChild(style);
    while ((current = document.elementFromPoint(x, y)) && elements.indexOf(current) === -1) {
      // push the element and its current style
      elements.push(current);
      previousPointerEvents.push({
        value: current.style.getPropertyValue(cssProp),
        priority: current.style.getPropertyPriority(cssProp)
      });
      // add "pointer-events: none", to get to the underlying element
      current.style.setProperty(cssProp, cssDisableVal, 'important');
    }
    // restore the previous pointer-events values
    for (i = previousPointerEvents.length; !!(d = previousPointerEvents[--i]); ) {
      elements[i].style.setProperty(cssProp, d.value ? d.value : '', d.priority);
    }
    // teardown;
    document.head.removeChild(style);
    return elements;
  };
}
```
- example usage
```shell
...
    }
    // teardown;
    document.head.removeChild(style);
    return elements;
  };
};
if (typeof window.addEventListener === 'function') {
  document.elementsFromPoint = axe.utils.pollyfillElementsFromPoint();
}
if (!Array.prototype.includes) {
  Array.prototype.includes = function(searchElement) {
    'use strict';
    var O = Object(this);
    var len = parseInt(O.length, 10) || 0;
    if (len === 0) {
...
```

#### <a name="apidoc.element.axe-core.utils.publishMetaData"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>publishMetaData (ruleResult)](#apidoc.element.axe-core.utils.publishMetaData)
- description and source-code
```javascript
publishMetaData = function (ruleResult) {
  'use strict';
  var checksData = axe._audit.data.checks || {};
  var rulesData = axe._audit.data.rules || {};
  var rule = axe.utils.findBy(axe._audit.rules, 'id', ruleResult.id) || {};
  ruleResult.tags = axe.utils.clone(rule.tags || []);
  var shouldBeTrue = extender(checksData, true);
  var shouldBeFalse = extender(checksData, false);
  ruleResult.nodes.forEach(function(detail) {
    detail.any.forEach(shouldBeTrue);
    detail.all.forEach(shouldBeTrue);
    detail.none.forEach(shouldBeFalse);
  });
  axe.utils.extendMetaData(ruleResult, axe.utils.clone(rulesData[ruleResult.id] || {}));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.axe-core.utils.queue"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>queue ()](#apidoc.element.axe-core.utils.queue)
- description and source-code
```javascript
function queue() {
  var tasks = [];
  var started = 0;
  var remaining = 0;
  // number of tasks not yet finished
  var completeQueue = noop;
  var complete = false;
  var err;
  // By default, wait until the next tick,
  // if no catch was set, throw to console.
  var defaultFail = function defaultFail(e) {
    err = e;
    setTimeout(function() {
      if (err !== undefined && err !== null) {
        axe.log('Uncaught error (of queue)', err);
      }
    }, 1);
  };
  var failed = defaultFail;
  function createResolve(i) {
    return function(r) {
      tasks[i] = r;
      remaining -= 1;
      if (!remaining && completeQueue !== noop) {
        complete = true;
        completeQueue(tasks);
      }
    };
  }
  function abort(msg) {
    // reset tasks
    completeQueue = noop;
    // notify catch
    failed(msg);
    // return unfinished work
    return tasks;
  }
  function pop() {
    var length = tasks.length;
    for (;started < length; started++) {
      var task = tasks[started];
      try {
        task.call(null, createResolve(started), abort);
      } catch (e) {
        abort(e);
      }
    }
  }
  var q = {
<span class="apidocCodeCommentSpan">    /**
* Defer a function that may or may not run asynchronously.
*
* First parameter should be the function to execute with subsequent
* parameters being passed as arguments to that function
*/
</span>    defer: function defer(fn) {
      if ((typeof fn === 'undefined' ? 'undefined' : _typeof(fn)) === 'object' && fn.then && fn.catch) {
        var defer = fn;
        fn = function fn(resolve, reject) {
          defer.then(resolve).catch(reject);
        };
      }
      funcGuard(fn);
      if (err !== undefined) {
        return;
      } else {
        if (complete) {
          throw new Error('Queue already completed');
        }
      }
      tasks.push(fn);
      ++remaining;
      pop();
      return q;
    },
    /**
* The callback to execute once all "deferred" functions have completed.  Will only be invoked once.
* @param  {Function} f The callback, receives an array of the return/callbacked
* values of each of the "deferred" functions
*/
    then: function then(fn) {
      funcGuard(fn);
      if (completeQueue !== noop) {
        throw new Error('queue 'then' already set');
      }
      if (!err) {
        completeQueue = fn;
        if (!remaining) {
          complete = true;
          completeQueue(tasks);
        }
      }
      return q;
    },
    'catch': function _catch(fn) {
      funcGuard(fn);
      if (failed !== defaultFail) {
        throw new Error('queue 'catch' already set');
      }
      if (!err) {
        failed = fn;
      } else {
        fn(err);
        err = null;
      }
      return q;
    },
    /**
* Abort the "queue" and prevent 'then' function from firing
* @param  {Function} fn The callback to execute; receives an array of the results which have completed
*/
    abort: abort
  };
  return q;
}
```
- example usage
```shell
...
* @param  {Context}   context The scope definition/context for analysis (include/exclude)
* @param  {Object}    options Options object to pass into rules and/or disable rules or checks
* @param  {Function} fn       Callback function to fire when audit is complete
*/
 Audit.prototype.run = function(context, options, resolve, reject) {
   'use strict';
   this.validateOptions(options);
   var q = axe.utils.queue();
   this.rules.forEach(function(rule) {
     if (axe.utils.ruleShouldRun(rule, context, options)) {
       q.defer(function(res, rej) {
         rule.run(context, options, res, function(err) {
           if (!options.debug) {
             var errResult = Object.assign(new RuleResult(rule), {
               result: axe.constants.CANTTELL,
...
```

#### <a name="apidoc.element.axe-core.utils.respondable"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>respondable (win, topic, message, keepalive, callback)](#apidoc.element.axe-core.utils.respondable)
- description and source-code
```javascript
function respondable(win, topic, message, keepalive, callback) {
  var id = uuid.v1();
  post(win, topic, message, id, keepalive, callback);
}
```
- example usage
```shell
...
      resolve(null);
    } else {
      reject(errMsg);
    }
  }, 0);
}, 500);
// send 'axe.ping' to the frame
axe.utils.respondable(win, 'axe.ping', null, undefined, function() {
  clearTimeout(timeout);
  // Give aXe 30s to respond to 'axe.start'
  timeout = setTimeout(function() {
    reject(err('Axe in frame timed out', node));
  }, 3e4);
  // send 'axe.start' and send the callback if it responded
  axe.utils.respondable(win, 'axe.start', parameters, undefined, function(data) {
...
```

#### <a name="apidoc.element.axe-core.utils.ruleShouldRun"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>ruleShouldRun (rule, context, options)](#apidoc.element.axe-core.utils.ruleShouldRun)
- description and source-code
```javascript
ruleShouldRun = function (rule, context, options) {
  'use strict';
  var runOnly = options.runOnly || {};
  var ruleOptions = (options.rules || {})[rule.id];
  // Never run page level rules if the context is not on the page
  if (rule.pageLevel && !context.page) {
    return false;
  } else {
    if (runOnly.type === 'rule') {
      return runOnly.values.indexOf(rule.id) !== -1;
    } else {
      if (ruleOptions && typeof ruleOptions.enabled === 'boolean') {
        return ruleOptions.enabled;
      } else {
        if (runOnly.type === 'tag' && runOnly.values) {
          return matchTags(rule, runOnly.values);
        } else {
          return matchTags(rule, []);
        }
      }
    }
  }
}
```
- example usage
```shell
...
* @param  {Function} fn       Callback function to fire when audit is complete
*/
 Audit.prototype.run = function(context, options, resolve, reject) {
   'use strict';
   this.validateOptions(options);
   var q = axe.utils.queue();
   this.rules.forEach(function(rule) {
     if (axe.utils.ruleShouldRun(rule, context, options)) {
       q.defer(function(res, rej) {
         rule.run(context, options, res, function(err) {
           if (!options.debug) {
             var errResult = Object.assign(new RuleResult(rule), {
               result: axe.constants.CANTTELL,
               description: 'An error occured while running this rule',
               message: err.message,
...
```

#### <a name="apidoc.element.axe-core.utils.select"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>select (selector, context)](#apidoc.element.axe-core.utils.select)
- description and source-code
```javascript
function select(selector, context) {
  'use strict';
  var result = [], candidate;
  for (var i = 0, l = context.include.length; i < l; i++) {
    candidate = context.include[i];
    if (candidate.nodeType === candidate.ELEMENT_NODE && axe.utils.matchesSelector(candidate, selector)) {
      pushNode(result, [ candidate ], context);
    }
    pushNode(result, candidate.querySelectorAll(selector), context);
  }
  return result.sort(axe.utils.nodeSorter);
}
```
- example usage
```shell
...
this.initiator = spec && typeof spec.initiator === 'boolean' ? spec.initiator : true;
this.page = false;
spec = normalizeContext(spec);
this.exclude = spec.exclude;
this.include = spec.include;
this.include = parseSelectorArray(this, 'include');
this.exclude = parseSelectorArray(this, 'exclude');
axe.utils.select('frame, iframe', this).forEach(function(frame) {
  if (isNodeInContext(frame, self)) {
    pushUniqueFrame(self.frames, frame);
  }
});
if (this.include.length === 1 && this.include[0] === document) {
  this.page = true;
}
...
```

#### <a name="apidoc.element.axe-core.utils.sendCommandToFrame"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>sendCommandToFrame (node, parameters, resolve, reject)](#apidoc.element.axe-core.utils.sendCommandToFrame)
- description and source-code
```javascript
sendCommandToFrame = function (node, parameters, resolve, reject) {
  'use strict';
  var win = node.contentWindow;
  if (!win) {
    axe.log('Frame does not have a content window', node);
    resolve(null);
    return;
  }
  // give the frame .5s to respond to 'axe.ping', else log failed response
  var timeout = setTimeout(function() {
    // This double timeout is important for allowing iframes to respond
    // DO NOT REMOVE
    timeout = setTimeout(function() {
      var errMsg = err('No response from frame', node);
      if (!parameters.debug) {
        axe.log(errMsg);
        resolve(null);
      } else {
        reject(errMsg);
      }
    }, 0);
  }, 500);
  // send 'axe.ping' to the frame
  axe.utils.respondable(win, 'axe.ping', null, undefined, function() {
    clearTimeout(timeout);
    // Give aXe 30s to respond to 'axe.start'
    timeout = setTimeout(function() {
      reject(err('Axe in frame timed out', node));
    }, 3e4);
    // send 'axe.start' and send the callback if it responded
    axe.utils.respondable(win, 'axe.start', parameters, undefined, function(data) {
      clearTimeout(timeout);
      if (data instanceof Error === false) {
        resolve(data);
      } else {
        reject(data);
      }
    });
  });
}
```
- example usage
```shell
...
    } catch (err) {
      rej(err);
    }
  });
});
axe.utils.toArray(document.querySelectorAll('frame, iframe')).forEach(function(frame) {
  q.defer(function(res, rej) {
    return axe.utils.sendCommandToFrame(frame, {
      command: 'cleanup-plugin'
    }, res, rej);
  });
});
q.then(function(results) {
  if (cleanupErrors.length === 0) {
    resolve(results);
...
```

#### <a name="apidoc.element.axe-core.utils.toArray"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>toArray (thing)](#apidoc.element.axe-core.utils.toArray)
- description and source-code
```javascript
toArray = function (thing) {
  'use strict';
  return Array.prototype.slice.call(thing);
}
```
- example usage
```shell
...
  function parseSelectorArray(context, type) {
'use strict';
var item, result = [];
for (var i = 0, l = context[type].length; i < l; i++) {
  item = context[type][i];
  // selector
  if (typeof item === 'string') {
    result = result.concat(axe.utils.toArray(document.querySelectorAll(item)));
    break;
  } else {
    if (item && item.length && !(item instanceof Node)) {
      if (item.length > 1) {
        pushUniqueFrameSelector(context, type, item);
      } else {
        result = result.concat(axe.utils.toArray(document.querySelectorAll(item[0])));
...
```

#### <a name="apidoc.element.axe-core.utils.tokenList"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>tokenList (str)](#apidoc.element.axe-core.utils.tokenList)
- description and source-code
```javascript
tokenList = function (str) {
  'use strict';
  return str.trim().replace(/\s{2,}/g, ' ').split(' ');
}
```
- example usage
```shell
...
        }
        switch (attrInfo.type) {
case 'boolean':
case 'nmtoken':
 return typeof value === 'string' && attrInfo.values.indexOf(value.toLowerCase()) !== -1;

case 'nmtokens':
 list = axe.utils.tokenList(value);
 // Check if any value isn't in the list of values
 return list.reduce(function(result, token) {
   return result && attrInfo.values.indexOf(token) !== -1;
 }, list.length !== 0);

case 'idref':
 return !!(value && doc.getElementById(value));
...
```



# <a name="apidoc.module.axe-core.utils.DqElement"></a>[module axe-core.utils.DqElement](#apidoc.module.axe-core.utils.DqElement)

#### <a name="apidoc.element.axe-core.utils.DqElement.DqElement"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>DqElement (element, spec)](#apidoc.element.axe-core.utils.DqElement.DqElement)
- description and source-code
```javascript
function DqElement(element, spec) {
  'use strict';
  spec = spec || {};
<span class="apidocCodeCommentSpan">  /**
* A unique CSS selector for the element
* @type {String}
*/
</span>  this.selector = spec.selector || [ axe.utils.getSelector(element) ];
  /**
* Xpath to the element
*/
  this.xpath = spec.xpath || [ axe.utils.getXpath(element) ];
  /**
* The generated HTML source code of the element
* @type {String}
*/
  this.source = spec.source !== undefined ? spec.source : getSource(element);
  /**
* The element which this object is based off or the containing frame, used for sorting.
* Excluded in toJSON method.
* @type {HTMLElement}
*/
  this.element = element;
}
```
- example usage
```shell
...
          });
          result[r.type] = res;
          if (res.length) {
            hasResults = true;
          }
        });
        if (hasResults) {
          result.node = new axe.utils.DqElement(node);
          ruleResult.nodes.push(result);
        }
      }
      resolveNode();
    }).catch(rejectNode);
  });
}
...
```

#### <a name="apidoc.element.axe-core.utils.DqElement.fromFrame"></a>[function <span class="apidocSignatureSpan">axe-core.utils.DqElement.</span>fromFrame (node, frame)](#apidoc.element.axe-core.utils.DqElement.fromFrame)
- description and source-code
```javascript
fromFrame = function (node, frame) {
  node.selector.unshift(frame.selector);
  node.xpath.unshift(frame.xpath);
  return new axe.utils.DqElement(frame.element, node);
}
```
- example usage
```shell
...
var frameXpath = axe.utils.getXpath(frameElement);
var frameSpec = {
  element: frameElement,
  selector: frameSelector,
  xpath: frameXpath
};
resultSet.forEach(function(res) {
  res.node = axe.utils.DqElement.fromFrame(res.node, frameSpec);
  var checks = axe.utils.getAllChecks(res);
  if (checks.length) {
    checks.forEach(function(check) {
      check.relatedNodes = check.relatedNodes.map(function(node) {
        return axe.utils.DqElement.fromFrame(node, frameSpec);
      });
    });
...
```



# <a name="apidoc.module.axe-core.utils.DqElement.prototype"></a>[module axe-core.utils.DqElement.prototype](#apidoc.module.axe-core.utils.DqElement.prototype)

#### <a name="apidoc.element.axe-core.utils.DqElement.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">axe-core.utils.DqElement.prototype.</span>toJSON ()](#apidoc.element.axe-core.utils.DqElement.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  'use strict';
  return {
    selector: this.selector,
    source: this.source,
    xpath: this.xpath
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.axe-core.utils.respondable"></a>[module axe-core.utils.respondable](#apidoc.module.axe-core.utils.respondable)

#### <a name="apidoc.element.axe-core.utils.respondable.respondable"></a>[function <span class="apidocSignatureSpan">axe-core.utils.</span>respondable (win, topic, message, keepalive, callback)](#apidoc.element.axe-core.utils.respondable.respondable)
- description and source-code
```javascript
function respondable(win, topic, message, keepalive, callback) {
  var id = uuid.v1();
  post(win, topic, message, id, keepalive, callback);
}
```
- example usage
```shell
...
      resolve(null);
    } else {
      reject(errMsg);
    }
  }, 0);
}, 500);
// send 'axe.ping' to the frame
axe.utils.respondable(win, 'axe.ping', null, undefined, function() {
  clearTimeout(timeout);
  // Give aXe 30s to respond to 'axe.start'
  timeout = setTimeout(function() {
    reject(err('Axe in frame timed out', node));
  }, 3e4);
  // send 'axe.start' and send the callback if it responded
  axe.utils.respondable(win, 'axe.start', parameters, undefined, function(data) {
...
```

#### <a name="apidoc.element.axe-core.utils.respondable.isInFrame"></a>[function <span class="apidocSignatureSpan">axe-core.utils.respondable.</span>isInFrame (win)](#apidoc.element.axe-core.utils.respondable.isInFrame)
- description and source-code
```javascript
isInFrame = function (win) {
  win = win || window;
  return !!win.frameElement;
}
```
- example usage
```shell
...
* @param  {context} context
* @return {Error}
*/
 function validateContext(context) {
   'use strict';
   if (context.include.length === 0) {
     if (context.frames.length === 0) {
       var env = axe.utils.respondable.isInFrame() ? 'frame' : 'page';
       return new Error('No elements found for include in ' + env + ' Context');
     }
     context.frames.forEach(function(frame, i) {
       if (frame.include.length === 0) {
         return new Error('No elements found for include in Context of frame ' + i);
       }
     });
...
```

#### <a name="apidoc.element.axe-core.utils.respondable.subscribe"></a>[function <span class="apidocSignatureSpan">axe-core.utils.respondable.</span>subscribe (topic, callback)](#apidoc.element.axe-core.utils.respondable.subscribe)
- description and source-code
```javascript
subscribe = function (topic, callback) {
  subscribers[topic] = callback;
}
```
- example usage
```shell
...
 /**
* Sets up Rules, Messages and default options for Checks, must be invoked before attempting analysis
* @param  {Object} audit The "audit specification" object
* @private
*/
 axe._load = function(audit) {
   'use strict';
   axe.utils.respondable.subscribe('axe.ping', function(data, keepalive, respond) {
     respond({
       axe: true
     });
   });
   axe.utils.respondable.subscribe('axe.start', runCommand);
   axe._audit = new Audit(audit);
 };
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

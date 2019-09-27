Camunda Consulting Examples
===========================

This repository contains examples, code snippets and demo applications build by the Camunda Consulting Team
or contributors. Note: All examples are only tested manually and there is no guarantee that they are actively maintained. If you search for officially maintained examples go to <a href="https://github.com/camunda/camunda-bpm-examples">https://github.com/camunda/camunda-bpm-examples</a>.  

<table>
  <tr>
    <th>Type of Example</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><a href="https://github.com/camunda/camunda-consulting/tree/master/snippets">Snippets</a></td>
    <td>Code snippets for particular technical issues. <b>The code is not maintained and might be out-of-date.</b></td>
  </tr>
  <tr>
    <td><a href="https://github.com/camunda/camunda-consulting/tree/master/one-time-examples">One-time Examples</a></td>
    <td>Examples created once for a specific event (like a conference or a magazine article). <b>The code is not maintained and might be out-of-date.</b></td>
  </tr>
</table>



Showcases
-----------------------

<table>
  <tr>
    <td>
      <a href="https://github.com/camunda/camunda-consulting/tree/master/one-time-examples/twitter">Review Process for new Tweets</a> <br />
<img src="one-time-examples/twitter/src/main/resources/TwitterDemoProcess.png" width="200" />
    </td>
    <td>
       Key Features showcased:
       <ul>
<li> Complete Process Application </li>
<li> HTML or JSF task forms </li>
<li> Testing with camunda-bpm-assert and PowerMock + Mockito </li>
<li> [todo] Cycle with Collaboration </li>
<li> [todo] Retries and Incident Handling </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/camunda/camunda-consulting/tree/master/one-time-examples/camel-use-cases">Camel Use Cases</a> <br />
<img src="https://raw.github.com/camunda/camunda-bpm-camel/master/use-cases.png" width="200" />
    </td>
    <td>
       Key Features showcased:
       <ul>
        <li>Features of Camel Component, especially including messaging</li>
      </ul>
    </td>
  </tr>
 <tr>
    <td>
      <a href="https://github.com/camunda/camunda-consulting/tree/master/one-time-examples/underwriting">Insurance Underwriting</a> <br />
<img src="one-time-examples/underwriting/docs/process-and-case.png" width="200" />
    </td>
    <td>
       Key Features showcased:
       <ul>
          <li>CMMN</li>
          <li>Case UI in JSF</li>
          <li>Combination of BPMN, CMMN and Rules</li>
      </ul>
    </td>
  </tr>  
 <tr>
    <td>
      <a href="https://github.com/camunda/camunda-consulting/tree/master/one-time-examples/incident-management">Incident Handling</a> <br />
<img src="one-time-examples/incident-management/src/main/resources/incidentManagement.png" width="200" />
    </td>
    <td>
       Key Features showcased:
       <ul>
          <li>Working process from official OMG by example paper</li>
          <li>BPMN Collaboration</li>
      </ul>
    </td>
  </tr>    

  <tr>
    <td>
      <a href="one-time-examples/en/skill-based-routing">Skill-based-Routing</a> <br />
      <img src="one-time-examples/en/skill-based-routing/doc/skill-based-routing-decision-flow.png" width="200" />
    </td>
    <td>
       Key Features showcased:
       <ul>
          <li>DMN Decision Tables</li>
          <li>Decision Flow implementing a DMN Decision Requirement Diagram (DRD)</li>
      </ul>
    </td>
  </tr>

</table>



Snippets
-----------------------

### Human Task Management

<table>
  <tr>
    <th>Preview</th>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><img src="snippets/subtask-checklist/screenshot.png" width="100" /></td>
    <td><a href="https://github.com/camunda/camunda-consulting/tree/master/snippets/subtask-checklist">Subtask Checklist</a></td>
    <td>BPMN process with sub tasks configured on a User Task using BPMN Extension Elements. The Subtasks are shown in the HTML task form using the Camunda Forms SDK (JavaScript). A User Task can only be completed if all subtasks are completed beforehand.</td>
  </tr>
  <tr>
    <td><img src="snippets/jsf-simple-tasklist/screenshot.png" width="100"></td>
    <td><a href="snippets/jsf-simple-tasklist">Simple tasklist build with JSF</a></td>
    <td>A tasklist to show how to use the engine api inside a JSF application. It calls forms, completes tasks and shows the detail process diagram with bpmn.io</td>
  </tr>
  <tr>
    <td><img src="snippets/task-overdue-job-handler/dueDate.png" width="100"></td>
    <td><a href="snippets/task-overdue-job-handler">Watch Task Due Date and Automatically Take Action</a></td>
    <td>A Process engine Plugin which registers Jobs for all User Tasks having a due date. It allows to define an own JobHandler to take action whenever a due date is hit, e.g sending an email.</td>
  </tr>
  <tr>
    <td><img src="snippets/single-task-process/src/main/resources/single-task-process.png" width="100"></td>
    <td><a href="snippets/single-task-process">Dynamic single task process</a></td>
    <td>A highly configurable process to get toDo items into your task list</td>
  </tr>
</table>

### BPMN

<table>
  <tr>
    <th>Preview</th>
    <th>Name</th>
    <th>Description</th>
  </tr>

  <tr>
    <td><img src="snippets/signal-event-interrupts-parallel-branch/src/main/resources/process.png" width="100"></td>
    <td><a href="snippets/signal-event-interrupts-parallel-branch">BPMN Signal Events between Parallel Branches</a></td>
    <td>This example shows how to interrupt a Task in a parallel flow within the same process instance by using a BPMN Signal Event.</td>
  </tr>
  <tr>
    <td><img src="snippets/i18n-process-model/translated-model.png" width="100"></td>
    <td><a href="snippets/i18n-process-model">Translate your process model on the fly</a></td>
    <td>Translate the BPMN XML on the fly using XPath and render the result (in the correct language) via bpmn.io</td>
  </tr>  
  <tr>
    <td><img src="snippets/call-activity-set-local-variable/src/main/resources/process.png" width="100"></td>
    <td><a href="snippets/call-activity-set-local-variable">Call Activity sets local variable</a></td>
    <td>Shows how to set a local variable in a parent process based on the variable of a child process invoked by a Call Activity.</td>
  </tr>  
  <tr>
    <td><img src="snippets/split-items-via-or-gateway/src/main/resources/process.png" width="100"></td>
    <td><a href="snippets/split-items-via-or-gateway">Split Order Item Handling via OR Gateway</a></td>
    <td>Assume only a few items of an order are decided in one go - but the approved ones need to get processed right away. This is modeled using an OR Gateway and local variables.</td>
  </tr>    
  <tr>
    <td><img src="snippets/bpmn-adhoc-task/src/main/resources/process.png" width="100" /></td>
    <td><a href="snippets/bpmn-adhoc-task/">Workaround to realize BPMN AdHoc Subpocess</a></td>
    <td>The BPMN AdHoc Subprocess is not specified to be executable, hence camunda BPM cannot execute it out-of-the-box. This snippet shows a possile workaround.</td>
  </tr>
  <tr>
    <td><img src="snippets/non-interrupting-message-event-sub-process-in-sub-process/src/main/resources/process.png" width="100"></td>
    <td><a href="snippets/non-interrupting-message-event-sub-process-in-sub-process">Non-interrupting Message Event Sub-Process inside a Sub-Process</a></td>
    <td>An example showing that a Sub-Process is not finished until a contained Event Sub-Process has reached its end.</td>
  </tr>
</table>

### Camunda Webapp (Tasklist & Cockpit)

<table>
  <tr>
    <th>Preview</th>
    <th>Name</th>
    <th>Description</th>
  </tr>

  <tr>
    <td><img src="snippets/camunda-webapp-customized/screenshot.png" width="100"></td>
    <td><a href="snippets/camunda-webapp-customized">Webapp Customizing</a></td>
    <td>Shows how to build a customized webapp (own logo, colors, language, plugins, ...) by using Maven Overlay.</td>
  </tr>

  <tr>
    <td><img src="https://i.vimeocdn.com/video/485755185_640.jpg" width="100"></td>
    <td><a href="http://camunda.org/plugins/">Various Cockpit Plugins</a></td>
    <td>The Plugin Store lists various available cockpit plugins, including the consulting snippets.</td>
  </tr>

  <tr>
    <td><img src="snippets/tasklist-plugin-easy-search/screenshot.png" width="100"></td>
    <td><a href="snippets/tasklist-plugin-easy-search">Tasklist Plugin: Easy Search</a></td>
    <td>Plugin that provides a "Google-like" search bar for tasks.</td>
  </tr>
  <tr>
    <td><img src="snippets/tasklist-plugin-nice-external-forms/screenshot.png" width="100"></td>
    <td><a href="snippets/tasklist-plugin-nice-external-forms">Tasklist Plugin: Extended External Forms</a></td>
    <td>Plugin that provides a customized and better looking external forms hook.</td>
  </tr>
  
</table>

### bpmn.io

<table>
  <tr>
    <th>Preview</th>
    <th>Name</th>
    <th>Description</th>
  </tr>

  <tr>
    <td><img src="snippets/bpmn-io-sample/screenshot.png" width="100"></td>
    <td><a href="snippets/bpmn-io-sample">Plain HTML page showing Process Instance status</a></td>
    <td>Shows how to build a self-contained HTML page with bpmn.io showing the process model and add overlays and markers to show historical information.</td>
  </tr>

  
</table>


### DMN

<table>
  <tr>
    <th>Preview</th>
    <th>Name</th>
    <th>Description</th>
  </tr>

  <tr>
    <td><img src="snippets/dmn-decision-chaining/decision-chaining-function2.png" width="100"></td>
    <td><a href="snippets/dmn-decision-chaining">DMN dependant decisions</a></td>
    <td>How to evaluate dependant DMN decisions on the Camunda BPM platform.</td>
  </tr>  
  
</table>

### CMMN
<table>
  <tr>
    <td><img src="snippets/cmmn-listener-extension/src/test/resources/assigned-tasks.png" width="100"></td>
    <td><a href="snippets/cmmn-listener-extension">CMMN Human Task Listener in a Process Engine Plugin</a></td>
    <td>Using task listener in all CMMN Human Tasks.</td>
  </tr>
</table>

### Process Engine Plugins

<table>
  <tr>
    <th>Preview</th>
    <th>Name</th>
    <th>Description</th>
  </tr>

  <tr>
    <td><img src="snippets/async-joins/src/main/resources/parallelSubprocess.png" width="100"></td>
    <td><a href="snippets/async-joins">Making parallel joins asynchronous</a></td>
    <td>To avoid optimistic lock exceptions on heavy load processes, this plugin makes each joining gateway asynchronous without further configuration in the process diagram.</td>
  </tr>

  <tr>
    <td><img src="http://docs.camunda.org/7.3/guides/user-guide/assets/img/transactions-2.png" width="100"></td>
    <td><a href="snippets/authenticated-async-continuation">authenticatedUserId after Asynchronous Continuation</a></td>
    <td>To use the userId after asynchronous continuation, this plugin puts it from the history on the current thread.</td>
  </tr>

  <tr>
    <td><img src="snippets/authorization-demo/src/main/resources/process.png" width="100"></td>
    <td><a href="snippets/authorization-demo">Authorized User Tasks</a></td>
    <td>Only authorized users are able to complete a task. Obsolete since 7.3. Use <a href="http://docs.camunda.org/7.3/guides/user-guide/#process-engine-authorization-service">Authorization-Service</a> instead.</td>
  </tr>

  <tr>
    <td><img src="http://docs.camunda.org/7.3/assets/img/user-guide/process-engine-history.png" width="100"></td>
    <td><a href="snippets/change-history-output">History Variable Filter</a></td>
    <td>How to store only one of many variables in the history.</td>
  </tr>

  <tr>
    <td><img src="snippets/change-job-retry/thumbnail.png" width="100"></td>
    <td><a href="snippets/change-job-retry">Change Number of Job Retries</a></td>
    <td>This snippet shows how to change the number of retries for all jobs without touching the process diagrams.</td>
  </tr>

  <tr>
    <td><img src="snippets/extended-serialization/extended-serialization-process/src/main/resources/process.png" width="100"></td>
    <td><a href="snippets/extended-serialization">Extend serialization of process variables</a></td>
    <td>This snippets exends the serialization of process variables for special classes, builds a jboss module with a maven plugin and shows how to use complex objects in a process application.</td>
  </tr>

  <tr>
    <td><img src="snippets/engine-plugin-add-save-points/screenshot.png" width="100"></td>
    <td><a href="snippets/engine-plugin-add-save-points">Engine Plugin: Add Save Points</a></td>
    <td>A plugin that automatically adds save points, i.e. asyncronous continuation or transaction boundaries, to certain BPMN elements.</td>
  </tr>

</table>

### Runtime Environments

<table>
  <tr>
    <th>Preview</th>
    <th>Name</th>
    <th>Description</th>
  </tr>
  
  <tr>
    <td><img src="http://docs.camunda.org/7.3/assets/img/getting-started/spring-framework/Spring_Logo.png" width="100"></td>
    <td><a href="snippets/spring-java-based-config">Java-based Spring container configuration</a></td>
    <td>Run the process application in a Spring container with java-based configuration on a shared process engine.</td>
  </tr>

  <tr>
    <td><img src="snippets/embedded-engine-without-spring/Spring_Logo-striked-through.png" width="100"></td>
    <td><a href="snippets/embedded-engine-without-spring">Embedded Process Engine without Spring</a></td>
    <td>A Process Application containing an embedded process engine that is configured in the processes.xml file and therefore does not require the Spring Framework as a dependency.</td>
  </tr>
  
</table>

### Testing

<table>
  <tr>
    <th>Preview</th>
    <th>Name</th>
    <th>Description</th>
  </tr>
  
  <tr>
    <td><img src="snippets/bpmn-validation/screenshot.png" width="100"></td>
    <td><a href="snippets/bpmn-validation">BPMN Validation with the Parser of the Process Engine</a></td>
    <td>A minimal environment for validating BPMN processes using an in-memory process engine in a JUnit test.</td>
  </tr>

</table>

### Administration

<table>
  <tr>
    <th>Preview</th>
    <th>Name</th>
    <th>Description</th>
  </tr>
  
  <tr>
    <td><img src="snippets/clean-up-history/cleanup.jpg" width="100"></td>
    <td><a href="snippets/clean-up-history">How to clean up the history tables</a></td>
    <td>Solutions to clean up the history from old completed process instances.</td>
  </tr>

</table>

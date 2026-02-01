---
layout: default
title: "DSA | Kartik Patel"
---

# Kartik Patel | DSA Notes

<div class="dsa-container">
  <div class="dsa-sidebar">
    <h3>Topics</h3>
    <ul>
      <li class="active" onclick="showTopic('array')">Complete Array Problems & Resources Guide</li>
      <li onclick="showTopic('strings')">Strings</li>
      <li onclick="showTopic('linkedlist')">Linked List</li>
      <li onclick="showTopic('stack')">Stack & Queue</li>
      <li onclick="showTopic('dp')">Dynamic Programming</li>
      <li onclick="showTopic('graph')">Graphs</li>
    </ul>
  </div>

  <div class="dsa-content">
    <div id="array" class="topic active">
      <h2>Complete Array Problems & Resources Guide</h2>
      <p>Add your array problems and resources here.</p>
    </div>

    <div id="strings" class="topic">
      <h2>Strings</h2>
      <p>Add your string problems and resources here.</p>
    </div>

    <div id="linkedlist" class="topic">
      <h2>Linked List</h2>
      <p>Add your linked list problems and resources here.</p>
    </div>

    <div id="stack" class="topic">
      <h2>Stack & Queue</h2>
      <p>Add your stack and queue problems and resources here.</p>
    </div>

    <div id="dp" class="topic">
      <h2>Dynamic Programming</h2>
      <p>Add your dynamic programming problems and resources here.</p>
    </div>

    <div id="graph" class="topic">
      <h2>Graphs</h2>
      <p>Add your graph problems and resources here.</p>
    </div>
  </div>
</div>

<script>
  function showTopic(topicId) {
    const topics = document.querySelectorAll('.topic');
    topics.forEach(t => t.classList.remove('active'));

    const items = document.querySelectorAll('.dsa-sidebar ul li');
    items.forEach(i => i.classList.remove('active'));

    document.getElementById(topicId).classList.add('active');
    event.target.classList.add('active');
  }
</script>

<style>
  .dsa-container {
    display: flex;
    max-width: 1000px;
    margin: 20px auto;
    border: 1px solid #cbd5e1;
    border-radius: 8px;
    overflow: hidden;
    height: 600px;
  }

  .dsa-sidebar {
    width: 250px;
    background: #f1f5f9;
    border-right: 1px solid #cbd5e1;
    padding: 20px;
  }

  .dsa-sidebar h3 {
    margin-top: 0;
    margin-bottom: 10px;
  }

  .dsa-sidebar ul {
    list-style: none;
    padding: 0;
  }

  .dsa-sidebar ul li {
    padding: 10px;
    cursor: pointer;
    border-radius: 5px;
  }

  .dsa-sidebar ul li:hover, .dsa-sidebar ul li.active {
    background: #2563eb;
    color: white;
  }

  .dsa-content {
    flex: 1;
    padding: 20px;
    overflow-y: auto;
    background: white;
  }

  .topic {
    display: none;
  }

  .topic.active {
    display: block;
  }
</style>

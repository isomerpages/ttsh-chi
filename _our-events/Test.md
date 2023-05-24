---
title: Test
permalink: /our-events/permalink/
description: ""
---



<style>
    .tab {
        display: flex;
    }
    
    .tab button {
        background-color: #f2f2f2;
        border: none;
        outline: none;
        cursor: pointer;
        padding: 10px 20px;
        transition: background-color 0.3s ease;
        width: 150px;
        text-align: left;
    }
    
    .tab button:hover {
        background-color: #ddd;
    }
    
    .tab button.active {
        background-color: #ccc;
    }
    
    .tabcontent {
        display: none;
        padding: 20px;
        background-color: #fff;
        border: 1px solid #ccc;
        width: 400px;
        height: 300px;
    }
</style>

	
	
    <div class="tab">
        <button class="tablinks">Tab 1</button>
        <button class="tablinks">Tab 2</button>
        <button class="tablinks">Tab 3</button>
    </div>

    <div id="Tab1" class="tabcontent">
        <h3>Content for Tab 1</h3>
        <p>This is the content for Tab 1.</p>
    </div>

    <div id="Tab2" class="tabcontent">
        <h3>Content for Tab 2</h3>
        <p>This is the content for Tab 2.</p>
    </div>

    <div id="Tab3" class="tabcontent">
        <h3>Content for Tab 3</h3>
        <p>This is the content for Tab 3.</p>
    </div>

    



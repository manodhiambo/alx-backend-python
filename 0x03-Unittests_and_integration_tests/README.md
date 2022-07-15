<center><h1>0x03. Unittests and Integration Tests</h1></center>

<b>UnitTests
Back-end
Integration tests</b>

<img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/1/f088970b450e82c881ea.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220715%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220715T050151Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=bbe51ad42b98728f752cd3f5d2a62a7e313b9171ee4adace390717abe8addcf7.gif">

<p>
<b>Unit testing is the process of testing that a particular function returns expected results for different set of inputs. A unit test is supposed to test standard inputs and corner cases. A unit test should only test the logic defined inside the tested function. Most calls to additional functions should be mocked, especially if they make network or database calls.

The goal of a unit test is to answer the question: if everything defined outside this function works as expected, does this function work as expected?

Integration tests aim to test a code path end-to-end. In general, only low level functions that make external calls such as HTTP requests, file I/O, database I/O, etc. are mocked.

Integration tests will test interactions between every part of your code.

Execute your tests with

$ python -m unittest path/to/test_file.py</b>
</p>

<h2>Resources</h2>

<p>
<b>Read or watch:</b>
<ul>
<li><a href="https://alx-intranet.hbtn.io/rltoken/a_AEObGK8jeqPtTPmm-gIA">unittest -  Unit testing framework</a></li>
<li><a href="https://alx-intranet.hbtn.io/rltoken/PKetnACd7FfRiU8_kpe5EA">unittest.mock -  mock object library</a></li>
<li><a href="https://alx-intranet.hbtn.io/rltoken/2ueVPK1kWZuz525FvZ1v2Q">eHow to mock a readonly property with mock?</a></li>
<li><a href="https://alx-intranet.hbtn.io/rltoken/mI7qc3Y42aZ7GTlLXDxgEg">parameterized</a></li>
<li><a href="https://alx-intranet.hbtn.io/rltoken/x83Hdr54q4Vax5xQ2Z3HSA">Memoization</a></li>
</ul>
</p>

<h2>Learning Objectives</h2>

<p>
At the end of this project, you are expected to be able to <a href="https://alx-intranet.hbtn.io/rltoken/NfT-nNKrNHGrDMY-Qm-1Dg">explain to anyone</a>, <b>without the help of Google:</b>

<ul>
<li>The difference between unit and integration tests.</li>
<li>Common testing patterns such as mocking, parametrizations and fixtures</li>
</ul>
</p>

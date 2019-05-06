# Final-Project-for-WAT

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
  
  <title>Title</title>
   
   <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
   
   <script>
        function getGrade(letterGrade){
            if (letterGrade == "A") {
                return 4;
            } else if (letterGrade == "B") {
                return 3;
            } else if (letterGrade == "C") {
                return 2;
            } else if (letterGrade == "D") {
                return 1;
            } else if (letterGrade == "F") {
                return 0;
            }
        }

function calc(){
    var ocount = 0 , ogpa = 0
    var bcount = 0 , bgpa = 0
    var mcount = 0 , mgpa = 0

    var gen01 =document.getElementById("gen01").value;
    var gen02 =document.getElementById("gen02").value;
    var gen03 =document.getElementById("gen03").value;
    var gen04 =document.getElementById("gen04").value;
    var gen05 =document.getElementById("gen05").value;
    var gen06 =document.getElementById("gen06").value;
    var gen07 =document.getElementById("gen07").value;
    var gen08 =document.getElementById("gen08").value;
    var gen09 =document.getElementById("gen09").value;
    var gen10 =document.getElementById("gen10").value;
    var gen11 =document.getElementById("gen11").value;
    var gen12 =document.getElementById("gen12").value;
    var gen13 =document.getElementById("gen13").value;
    var gen14 =document.getElementById("gen14").value;
    var gen15 =document.getElementById("gen15").value;
    var gen16 =document.getElementById("gen16").value;
    var bis01 =document.getElementById("bis01").value;
    var bis02 =document.getElementById("bis02").value;
    var bis03 =document.getElementById("bis03").value;
    var bis04 =document.getElementById("bis04").value;
    var bis05 =document.getElementById("bis05").value;
    var bis06 =document.getElementById("bis06").value;
    var bis07 =document.getElementById("bis07").value;
    var bis08 =document.getElementById("bis08").value;
    var bis09 =document.getElementById("bis09").value;
    var bis10 =document.getElementById("bis10").value;
    var bis11 =document.getElementById("bis11").value;
    var bis12 =document.getElementById("bis12").value;
    var bis13 =document.getElementById("bis13").value;
    var maj01 =document.getElementById("maj01").value;
    var maj02 =document.getElementById("maj02").value;
    var maj03 =document.getElementById("maj03").value;
    var maj04 =document.getElementById("maj04").value;
    var maj05 =document.getElementById("maj05").value;
    var maj06 =document.getElementById("maj06").value;
    var maj07 =document.getElementById("maj07").value;
    var maj08 =document.getElementById("maj08").value;
    var maj09 =document.getElementById("maj09").value;
    var maj10 =document.getElementById("maj10").value;
    var maj11 =document.getElementById("maj11").value;
    var maj12 =document.getElementById("maj12").value;


    if (gen01 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen01);
    }

    if (gen02 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen02);
    }
    if (gen03 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen03);
    }
    if (gen04 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen04);
    }
    if (gen05 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen05);
    }
    if (gen06 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen06);
    }
    if (gen07 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen07);
    }
    if (gen08 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen08);
    }
    if (gen09 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen09);
    }
    if (gen10 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen10);
    }
    if (gen11 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen11);
    }
    if (gen12 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen12);
    }
    if (gen13 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen13);
    }
    if (gen14 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen14);
    }
    if (gen15 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen15);
    }
    if (gen16 != "-") {
        ocount = ocount + 1;
        ogpa = ogpa + getGrade(gen16);
    }

    if (bis01 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis01);
        bgpa = bgpa + getGrade(bis01);
    }
    if (bis02 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis02);
        bgpa = bgpa + getGrade(bis02);
    }
    if (bis03 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis03);
        bgpa = bgpa + getGrade(bis03);
    }
    if (bis04 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis04);
        bgpa = bgpa + getGrade(bis04);
    }
    if (bis05 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis05);
        bgpa = bgpa + getGrade(bis05);
    }
    if (bis06 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis06);
        bgpa = bgpa + getGrade(bis06);
    }
    if (bis07 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis07);
        bgpa = bgpa + getGrade(bis07);
    }
    if (bis08 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis08);
        bgpa = bgpa + getGrade(bis08);
    }
    if (bis09 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis09);
        bgpa = bgpa + getGrade(bis09);
    }
    if (bis10 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis10);
        bgpa = bgpa + getGrade(bis10);
    }
    if (bis011 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis11);
        bgpa = bgpa + getGrade(bis11);
    }
    if (bis12 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis12);
        bgpa = bgpa + getGrade(bis12);
    }
    if (bis13 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        ogpa = ogpa + getGrade(bis13);
        bgpa = bgpa + getGrade(bis13);
    }
    if (maj01 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj01);
        bgpa = bgpa + getGrade(maj01);
        mgpa = mgpa + getGrade(maj01);
    }
    if (maj02 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj02);
        bgpa = bgpa + getGrade(maj02);
        mgpa = mgpa + getGrade(maj02);
    }
    if (maj03 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj03);
        bgpa = bgpa + getGrade(maj03);
        mgpa = mgpa + getGrade(maj03);
    }
    if (maj04 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj04);
        bgpa = bgpa + getGrade(maj04);
        mgpa = mgpa + getGrade(maj04);
    }
    if (maj05 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj05);
        bgpa = bgpa + getGrade(maj05);
        mgpa = mgpa + getGrade(maj05);
    }
    if (maj06 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj06);
        bgpa = bgpa + getGrade(maj06);
        mgpa = mgpa + getGrade(maj06);
    }
    if (maj07 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj07);
        bgpa = bgpa + getGrade(bis07);
        mgpa = mgpa + getGrade(maj07);
    }
    if (maj08 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj08);
        bgpa = bgpa + getGrade(maj08);
        mgpa = mgpa + getGrade(maj08);
    }
    if (maj09 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj09);
        bgpa = bgpa + getGrade(maj09);
        mgpa = mgpa + getGrade(maj09);
    }
    if (maj10 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj10);
        bgpa = bgpa + getGrade(maj10);
        mgpa = mgpa + getGrade(maj10);
    }
    if (maj11 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj11);
        bgpa = bgpa + getGrade(maj11);
        mgpa = mgpa + getGrade(maj11);
    }
    if (maj12 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj12);
        bgpa = bgpa + getGrade(maj12);
        mgpa = mgpa + getGrade(maj12);
    }
    if (maj13 != "-") {
        ocount = ocount + 1;
        bcount = bcount + 1;
        mcount = mcount + 1;
        ogpa = ogpa + getGrade(maj13);
        bgpa = bgpa + getGrade(maj13);
        mgpa = mgpa + getGrade(maj13);
    }
    document.getElementById("ogpa").innerText = ogpa / ocount;
    document.getElementById("bgpa").innerText = bgpa / bcount;
    document.getElementById("mgpa").innerText = mgpa / mcount;



}

    </script>
</head>
<body>
    <div class="container"><nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">GradeTracker</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                </li>
            </ul>

        </div>
    </nav>
    <h2>Schema</h2>
        <table class="table">
            <thead>
            <tr>
                <th scope="col">#</th>
                <th scope="col">Course</th>
                <th scope="col">Credits</th>
                <th scope="col">Grade</th>
            </tr>
            </thead>
            <tbody>
            <tr>
                <th scope="row">1</th>
                <td>English 101</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen01">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">2</th>
                <td>Algebra II</td>
                <td>4</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen02">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">3</th>
                <td>French I</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen03">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">4</th>
                <td>Business Problem Solving</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj01">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">5</th>
                <td>Intro to African-American History</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen04">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">6</th>
                <td>Business Orientation</td>
                <td>1</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis01">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">7</th>
                <td>English 105</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen05">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">8</th>
                <td>Applied Calculus</td>
                <td>4</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen06">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">9</th>
                <td>French II</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen07">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">10</th>
                <td>Intro to Psychology</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen08">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">11</th>
                <td>Swimming</td>
                <td>1</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen09">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">12</th>
                <td>Business Orientation II</td>
                <td>1</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis02">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">13</th>
                <td>Statistics - Bus. & Economics</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen10">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">14</th>
                <td>Principles of Economics I</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen11">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">15</th>
                <td>Accounting Principles I</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis03">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">16</th>
                <td>Management Information Systems</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="mag01">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">17</th>
                <td>Career Counseling</td>
                <td>1</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis04">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr><tr>
                <th scope="row">18</th>
                <td>Political Science</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen12">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">19</th>
                <td>Principles of Economics II</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen13">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">20</th>
                <td>Accounting Principles II</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis05">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">21</th>
                <td>Intro to Software Design</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj02">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">22</th>
                <td>Business Communications</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis06">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">23</th>
                <td>Quantitative Bus. Analytics</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj03">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">24</th>
                <td>Database Management</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj04">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">25</th>
                <td>Management & Org. Behavior</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis07">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">26</th>
                <td>Physical Science</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen14">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">27</th>
                <td>Principles of Marketing</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis08">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">28</th>
                <td>Production & Operations Management</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj05">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">29</th>
                <td>Intro to Data & Network Communication</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj06">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">30</th>
                <td>Finance Principles</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis09">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">31</th>
                <td>Business Law</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis10">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">32</th>
                <td>Systems Analysis & Design</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj07">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">33</th>
                <td>Cyber Security</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj08">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">34</th>
                <td>Web Authoring Tools</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj09">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">35</th>
                <td>Intro to eBusiness & Commerce</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj10">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">36</th>
                <td>Managerial Economics</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis11">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr><tr>
                <th scope="row">37</th>
                <td>Abnormal Psychology</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen15">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">38</th>
                <td>Information Systems Consulting</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj11">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">39</th>
                <td>Entrepreneurship</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis12">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">40</th>
                <td>Network Security</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="maj12">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">41</th>
                <td>Intro to Philosophy</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="gen16">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            <tr>
                <th scope="row">42</th>
                <td>Business Policy</td>
                <td>3</td>
                <td><div class="form-group">
                    <select class="form-control" id="bis13">
                        <option>-</option>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                        <option>D</option>
                        <option>F</option>
                    </select>
                </div></td>
            </tr>
            </tbody>
        </table>
        <div class="row">
            <button type="button" onclick="calc">Calculate</button>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-sm">
                    Overall GPA
                </div>
                <div class="col-sm">
                    Business GPA
                </div>
                <div class="col-sm">
                    Major GPA
                </div>
            </div><div class="row">
                <div class="col-sm" id="ogpa">
                    0
                </div>
                <div class="col-sm" id="bgpa">
                    0
                </div>
                <div class="col-sm" id="mgpa">
                    0
                </div>
        </div>
    </div>



    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
</body>

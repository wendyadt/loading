# loading
<!DOCTYPE html>
<html>

<head>
    <title>Loading Screen</title>
    <link rel="shortcut icon" href="lambang.png">
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="Loading2.css">
    <script type="text/javascript" src="Loading3.js"></script>
</head>
<div id="preloader">
    <div id="status"></div>
    <div class="container">
        <div class="row">
            <div class="animationload">
                <div class="loader"></div>
            </div>
        </div>
    </div>
</div>

<body>
    <div class="container">
        <div class="row">
            <button type="button" class="btn btn-magick btn-lg btn3d" data-toggle="modal" data-target="#tombol">KLIK</button>
            <div class="modal fade" id="tombol">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h4 class="modal-title">Loading . . .</h4>
                            <button type="button" class="close" data-dismiss="modal">&times;</button>
                        </div>
                        <div class="modal-body">
                            <div class="progress-outer">
                                <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped active" style="width:85%; box-shadow:-1px 10px 10px rgb(0, 0, 0));"></div>
                                    <div class="progress-value">85%</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>

</html>

### [Open Documentation](https://github.com/arekp09/Pallet-Configurator/wiki/0.-Documentation)

<div class="extra-margin">
    <div class="panel panel-primary">
        <div class="panel-heading">
            <div class="panel-title">
                <h2>About Pallet Configurator</h2>
            </div>
        </div>
        <div class="panel-body">
            <p class="lead">This application was developed to visualise and calculate different options of stacking boxes on pallet.</p>
            <h3>Used technologies:</h3>
            <ul>
                <li>C# with ASP.NET Core 2.1 (+ xUnit)</li>
                <li>JavaScript (Three.js, jQuery)</li>
                <li>CSS (Bootstrap)</li>
            </ul>
            <h2>Application walkthrough</h2>
            <h3>1. Fill in form</h3>
            <blockquote>
                <p>
                    First step is to fill in form which is binded with ASP.NET Model, pressing Confirm will POST Model to back-end
                    and calculate all stacking options.
                </p>
            </blockquote>
            <h3>2. Calculation</h3>
            <blockquote>
                <p>
                    Once Model is passed for calculation to back-end,
                    there are few options to calculate number of total boxes we can put on pallet, layers, rows and columns
                    based on informations inputed. Also result is limited to maximum weight and height of a pallet.
                    Returned list is displayed in 'Select stacking option'. Once right one is selected, click on 'Load' button.
                </p>
            </blockquote>
            <h3>3. Choose best stacking option</h3>
            <blockquote>
                <p>
                    Returned list is displayed in 'Select stacking option'. Once right one is selected, click on 'Draw Pallet' button.
                </p>
            </blockquote>
            <h3>4. Draw 3D model</h3>
            <blockquote>
                <p>
                    Choosed option will be loaded in 'Pallet view'.
                </p>
            </blockquote>
        </div>
    </div>
</div>
Quickly generate form text area 

##The regex

name="([\s\S]*?)" title="([\s\S]*?)" type="([\s\S]*?)"

##The substitution

<div class="form-group"><label class="col-md-4 control-label">$2</label><div class="col-md-6"><textarea type="$3" class="form-control" name="$1"></textarea></div></div>

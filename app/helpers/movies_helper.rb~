module MoviesHelper
  # Checks if a number is odd:
  def oddness(count)
    count.odd? ?  "odd" :  "even"
  end
end

def title

	if params[:order] == 'title'
		return 'hilite'
	else
		''
	end	
end
	
def release_date
	
	if params[:order] == 'release_date'
		return 'hilite'
	else
		''
	end
end	

def checked_option(rating)

	params.has_key?(:ratings) && params[:ratings].has_key?(rating)
	
end

